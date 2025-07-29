
# 🎓 Student Performance Prediction - End-to-End ML Pipeline

This project is an end-to-end Machine Learning pipeline designed to predict **student math scores** based on various socio-economic and academic factors. It uses advanced regression models and follows a modular pipeline structure for scalability and reusability.

---

## 🚀 Project Overview

### 📌 Key Stages:
1. **Data Ingestion** – Load raw data, create train/test splits.
2. **Data Transformation** – Handle missing values, encode categorical variables, scale numerical features.
3. **Model Training** – Train and tune multiple regression models including ensemble and boosting algorithms.
4. **Evaluation** – Automatically evaluate models using R² score and save the best-performing model.

---

## 🧰 Tools & Technologies

| Tool/Library         | Purpose |
|----------------------|---------|
| **Pandas, NumPy**     | Data manipulation and numerical operations |
| **Scikit-learn**      | Model training, preprocessing, and evaluation |
| **XGBoost**           | Gradient boosting regression |
| **CatBoost**          | Advanced categorical boosting |
| **Python Logging**    | Logging important pipeline events |
| **Dataclasses**       | Configuration management |

---

## 📂 Project Structure

project-root/
│
├── src/
│ ├── components/
│ │ ├── data_ingestion.py
│ │ ├── data_transformation.py
│ │ └── model_trainer.py
│ ├── utils/
│ │ └── utils.py
│ ├── logger.py
│ └── exception.py
│
├── artifacts/ # Saved models and preprocessing objects
├── notebook/ # Jupyter notebooks (EDA, testing)
├── main.py # Pipeline entry point
├── requirements.txt
└── README.md




---

## ⚙️ How to Run

1. **Clone the repo**:
```bash
https://github.com/Sandeep-colab/mlproject-.git
cd student-performance-ml


pip install -r requirements.txt

python main.py
