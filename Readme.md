# 🧠 Data Science Project: Price Analysis

This repository contains a complete data science pipeline for analyzing and modeling housing price data (e.g., Ames Housing dataset). It includes end-to-end steps: data ingestion, preprocessing, feature engineering, model training, evaluation, and deployment logic.

---

## 📁 Project Structure
```
├── .venv/ # Python virtual environment
├── analysis/ # EDA notebooks and analysis
│ └── EDA.ipynb
├── data/ # Raw and processed data files
│ └── arcwvezip/
├── explanations/ # SHAP values, model explainability outputs
│ └── extracted_data/
├── runs/ # Output from pipeline runs
│ └── _trash/
├── artifacts/ # Saved models, transformers, etc.
├── datasets/ # Dataset definitions (YAML or data splits)
├── inputs/ # Input schema or test samples
├── metrics/ # Evaluation metrics from model runs
├── params/ # Model parameters
├── tags/ # Metadata tags
├── pipelines/ # ML pipeline code
│ └── deployment_pipeline.py
├── src/ # Source code for core data science logic
│ ├── data_splitter.py
│ ├── ingest_data.py
│ ├── feature_engineering.py
│ └── model_evaluator.py
├── steps/ # Pipeline steps (predict, load, etc.)
│ ├── dynamic_importer.py
│ ├── model_loader.py
│ └── predictor.py
├── run_pipeline.py # Main entry to run the pipeline
├── run_deployment.py # Entry to run deployed model
├── requirements.txt # Python dependencies
└── README.md # Project overview
```



---

## ⚙️ Features

- ✅ Exploratory Data Analysis (EDA) with `EDA.ipynb`
- ✅ Modular data pipeline using Python scripts
- ✅ Feature engineering and preprocessing
- ✅ Model evaluation with metrics and explainability
- ✅ Artifacts tracked for versioning and reuse
- ✅ Ready for deployment via `run_deployment.py`

---
# 🏠 House Prices Predictor System

A modular and extensible machine learning pipeline for predicting house prices using structured data. This project includes end-to-end components such as data ingestion, preprocessing, feature engineering, model training, evaluation, and deployment.

---

## 📦 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/sajal-123/prices-predictor-system.git
   cd prices-predictor-system

2. **Create a Virtual Enviroment**
   ```bash
      python -m venv .venv
      source .venv/bin/activate   # On Windows: .venv\Scripts\activate
      Install dependencies

      pip install -r requirements.txt
      Run the pipeline

      python run_pipeline.py
3. **📓 Notebooks**
```
    EDA.ipynb — Initial exploration of dataset features, missing values, distribution, and target correlation.
```

3. **🧪 Deployment**
```
Run the following to simulate or launch inference using the trained model:
python run_deployment.py
The model is loaded dynamically via steps/model_loader.py

Predictions are handled by steps/predictor.py
```

3. **🧰 Tech Stack**
```
Languages: Python

Libraries: NumPy, Pandas, Scikit-learn

Visualization: Matplotlib, Seaborn

Notebooks: Jupyter

Config/Metadata: YAML
```

4. **🙋‍♂️ Author**
```
Sajal Garg
Data Science Enthusiast | Full-Stack Developer

📫 Connect with me on LinkedIn


