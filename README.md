# 🧠 Arabic Handwritten Character Recognition (AHCD) — Deep Learning

Deep Learning project that recognizes **Arabic handwritten characters** using **CNN** and **MobileNetV2**.
The model achieved **97.92% accuracy** on the **AHCD** dataset by applying **data augmentation, normalization, and dropout**. :contentReference[oaicite:0]{index=0}

---

## ✨ Project goals
- Build a reliable classifier for Arabic handwritten characters.
- Compare a custom **CNN** baseline with a transfer-learning approach (**MobileNetV2**).
- Improve generalization using augmentation + regularization techniques.

---

## ✅ What’s included
- End-to-end notebook workflow:
  - Data loading & preprocessing
  - Data augmentation
  - Model building (CNN + MobileNetV2)
  - Training & evaluation
  - Performance reporting

📄 Notebook: `notebooks/DL_Narjis_Saleh_TP084083.ipynb`

---

## 🧰 Tech stack
- Python, Jupyter
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib / Seaborn

---

## 📊 Results (from CV)
- Dataset: **AHCD**
- Best accuracy: **97.92%**
- Key techniques: **Augmentation, Dropout, Normalization** :contentReference[oaicite:1]{index=1}

> If you want, you can add a screenshot of the training curves and confusion matrix here to make the repo look even stronger.

---

## 🚀 Run locally

### 1) Create environment
```bash
python -m venv .venv
# Windows:
.venv\Scripts\activate
# macOS/Linux:
source .venv/bin/activate
2) Install dependencies
bash
Copy code
pip install -r requirements.txt
3) Start Jupyter
bash
Copy code
jupyter notebook
📁 Repository structure
txt
Copy code
.
├── notebooks/
│   └── DL_Narjis_Saleh_TP084083.ipynb
├── requirements.txt
├── .gitignore
└── README.md
📝 Notes
If you plan to run on GPU, install the correct TensorFlow build for your system.

Avoid committing large datasets/models to GitHub (handled by .gitignore).
