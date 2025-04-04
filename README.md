# 🩺 Diabetes Analyzer

A Python-based analyzer that extracts patient data from PDF medical reports, predicts whether the patient is diabetic using a trained machine learning model, and classifies the type of diabetes (Type 1, Type 2, Type 3c, or Pre-Diabetes).

---

## 🚀 Features

- 📄 Upload and parse medical PDF reports using `pdfplumber`
- 🔍 Extract key health metrics like HbA1c, BMI, blood glucose, etc.
- 🧠 Predict diabetic condition using a pre-trained ML model
- 🩻 Classify diabetes type (Type 1, Type 2, Type 3c, Pre-Diabetic, or Non-Diabetic)
- 🧑‍💻 Simple GUI to select PDFs (using `tkinter`)
- 📈 Modular and scalable design

---

## 🛠 Tech Stack

- Python 3
- `pdfplumber` – for reading PDFs
- `scikit-learn` – for ML model and preprocessing
- `joblib` – for loading saved models
- `tkinter` – for file selection GUI
- `pandas`, `re`, `os`

---

## 📥 Installation

```bash
# Clone the repository
git clone https://github.com/your-username/diabetes-analyzer.git
cd diabetes-analyzer

# (Optional) Create and activate a virtual environment
python3 -m venv venv
source venv/bin/activate  # on Mac/Linux
venv\Scripts\activate     # on Windows

# Install dependencies
pip install -r requirements.txt
