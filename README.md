# 🛡️ Network Security Project - Phishing Detection

Welcome to the **Network Security - Phishing Detection** repository! This project focuses on building a robust machine learning pipeline to detect phishing attacks using network data. It covers data ingestion, validation, transformation, model training, and batch prediction, along with cloud integration and logging.

---

## 📂 Repository Structure

- `app.py` — Main application script.  
- `main.py` — Entry point for running pipeline components.  
- `push_data.py` — Script to upload data to cloud or pipeline.  
- `Dockerfile` — Containerization setup.  
- `README.md` — Documentation.  
- `requirements.txt` — Python dependencies.  
- `setup.py` — Package configuration.  
- `test_mongodb.py` — MongoDB integration tests.  
- `.gitignore` — Git ignore rules.

### Directories:

- `networksecurity/` — Core package containing:  
  - `cloud/` — Cloud sync tools (e.g., S3).  
  - `components/` — Data ingestion, validation, transformation, model training modules.  
  - `constant/` — Configuration constants.  
  - `entity/` — Data models for config and artifacts.  
  - `exception/` — Custom exception classes.  
  - `logging/` — Logging utilities.  
  - `pipeline/` — Training pipeline and batch prediction code.  
  - `utils/` — Utilities for metrics, estimators, and helpers.

- `data_schema/` — Schema definition for data validation (`schema.yaml`).  
- `final_model/` — Saved models and preprocessors (`model.pkl`, `preprocessor.pkl`).  
- `Network_Data/` — Phishing dataset CSV file.  
- `prediction_output/` — Output CSVs for batch prediction results.  
- `templates/` — HTML templates including `table.html`.  
- `valid_data/` — Validation datasets (e.g., `test.csv`).  
- `.github/workflows/` — CI/CD workflows (`main.yaml`).  
- `__pycache__/` — Python cache files.

---

## ⚙️ Setup & Installation

Clone the repo:  
git clone https://github.com/Aparna-k246/Network-security.git  
cd Network-security

Create and activate a virtual environment:  
python -m venv venv  
source venv/bin/activate  # Linux/macOS  
venv\Scripts\activate     # Windows

Install dependencies:  
pip install -r requirements.txt

Run the app or training pipeline:  
python app.py

---

## 🚀 Project Highlights

- End-to-end pipeline from data ingestion to model training and prediction.  
- Modular code structure for easy maintenance and extension.  
- Schema-based data validation to ensure input quality.  
- Integration with cloud storage for syncing data and models.  
- Custom logging and error handling for robustness.  
- Batch prediction feature with output saving.  

---

## 💼 Recruiter-Friendly Summary

This project demonstrates my skills in building scalable, maintainable machine learning pipelines tailored for cybersecurity applications, specifically phishing detection. It showcases expertise in:

- Data ingestion, validation, and transformation using modular Python code.  
- Building and training classification models to detect phishing attacks.  
- Implementing robust logging, error handling, and cloud integration (AWS S3).  
- Working with schema validation to maintain data quality.  
- Automating batch predictions with clean outputs suitable for production.  
- Experience with containerization (Docker) and CI/CD workflows.  

This project is a strong indicator of my ability to deliver end-to-end ML solutions in security-sensitive environments, making me a valuable addition to any data science or ML engineering team focused on cybersecurity.

---

## 📞 Connect with Me

- GitHub: Aparna-k246 (https://github.com/Aparna-k246)  
- LinkedIn: aparna-k (https://www.linkedin.com/in/aparna-k-628005167/)  
- Email: *Add your email here*

---

⭐ If this project helps you, please star the repo!

---

Stay safe and secure! 🔐🚀
