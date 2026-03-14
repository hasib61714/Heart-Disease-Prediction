<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:6E40C9,50:A855F7,100:06B6D4&height=200&section=header&text=Heart%20Disease%20Predictor&fontSize=44&fontColor=fff&animation=fadeIn&fontAlignY=38&desc=ML-Powered%20Cardiovascular%20Risk%20Assessment%20System&descAlignY=58&descSize=18" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/hasib61714/heart-disease-prediction/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge" alt="License: MIT" />
  </a>
  <a href="https://github.com/hasib61714/heart-disease-prediction/stargazers">
    <img src="https://img.shields.io/github/stars/hasib61714/heart-disease-prediction?style=for-the-badge&color=A855F7" alt="Stars" />
  </a>
  <a href="https://github.com/hasib61714/heart-disease-prediction/network/members">
    <img src="https://img.shields.io/github/forks/hasib61714/heart-disease-prediction?style=for-the-badge&color=06B6D4" alt="Forks" />
  </a>
</p>

---

## About

**Heart Disease Prediction System** is a machine learning–powered health risk tool that estimates a patient's likelihood of cardiovascular disease based on clinical input data. Multiple classification algorithms were trained and benchmarked — including Logistic Regression, Random Forest, and Support Vector Machine — to identify the highest-accuracy model. A **FastAPI** backend serves predictions in real time to a responsive **React** frontend, making the tool accessible to both clinicians and general users.

---

## Features

- **Instant Risk Prediction** — Submit patient vitals and receive a cardiovascular risk assessment in real time
- **Multi-Model Benchmarking** — Logistic Regression, Random Forest, and SVM trained and compared side by side
- **High Accuracy** — Best-performing model selected after rigorous cross-validation and evaluation
- **Data Preprocessing Pipeline** — Handles missing values, feature scaling, and outlier treatment automatically
- **Feature Engineering** — Key clinical indicators extracted and transformed for optimal model performance
- **Interactive React UI** — Clean form-based interface with immediate prediction results
- **Comprehensive Evaluation** — Confusion matrix, F1 score, precision, recall, and ROC-AUC reported

---

## Tech Stack

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,fastapi,react,sklearn&theme=dark" />
  </a>
</p>

| Layer | Technology |
|---|---|
| Frontend | React, Tailwind CSS |
| Backend | FastAPI (Python) |
| ML Framework | Scikit-learn |
| Data Processing | Pandas, NumPy |
| Model Algorithms | Logistic Regression, Random Forest, SVM |
| Visualization | Matplotlib, Seaborn |

---

## Getting Started

### Prerequisites

- Python >= 3.10 & pip
- Node.js >= 18 & npm

### Installation

```bash
# Clone the repository
git clone https://github.com/hasib61714/heart-disease-prediction.git
cd heart-disease-prediction

# Backend setup
cd backend
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
pip install -r requirements.txt

# Frontend setup
cd ../frontend
npm install
```

### Usage

```bash
# Start the FastAPI backend
cd backend
uvicorn main:app --reload

# Start the React frontend
cd frontend
npm run dev
```

Open [http://localhost:5173](http://localhost:5173). The API docs are available at [http://localhost:8000/docs](http://localhost:8000/docs).

---

## Project Structure

```
heart-disease-prediction/
├── backend/
│   ├── main.py
│   ├── model/
│   │   ├── train.py
│   │   └── heart_model.pkl
│   └── requirements.txt
└── frontend/
    └── src/
        ├── components/
        └── pages/
```

---

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m 'feat: add your feature'`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

---

## License

This project is licensed under the [MIT License](LICENSE).

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:06B6D4,50:A855F7,100:6E40C9&height=120&section=footer" width="100%" />
</p>

<p align="center">
  Made with dedication by <a href="https://github.com/hasib61714">Md. Hasibul Hasan</a>
</p>
