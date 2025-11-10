# KinichKakmo
CheeseCake
# KinichKakmo

KinichKakmo is a modular Python application designed for reproducible workflows, query pipelines, and branded UI experimentation.  
It was later rebranded as **Axilix**, but this repository preserves the original KinichKakmo identity for archival and reference purposes.

---

## ✨ Features
- Modular query functions for reproducible research
- Environment‑based configuration with `.env` support
- Simple, copy‑pasteable setup instructions
- UI customization (sidebar, body colors, branded themes)
- Extensible design for creative and technical projects

---

## ⚙️ Setup

### 1. Create and activate a virtual environment
```bash
python3 -m venv .venv
# macOS/Linux
source .venv/bin/activate
# Windows (PowerShell)
.venv\Scripts\activate

### 2. Install dependencies
pip install -r requirements.txt

### 3. Run the App
```bash
streamlit run KinichKakmo.py

### 4. Query examples
from kinichkakmo import query

# Simple keyword search
result = query("campaign finance")
print(result)

# Search by entity + year
result = query(entity="John Doe", year=2024)
print(result)

