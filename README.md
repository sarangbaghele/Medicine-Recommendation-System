# 🏥 Medicine Recommendation System (AI-Powered)

## 📌 Project Overview
The **Medicine Recommendation System** is an AI-driven solution that suggests medicines based on patient symptoms and reviews. It leverages **Natural Language Processing (NLP)** and **Machine Learning (ML)** to analyze patient feedback, perform sentiment analysis, and provide personalized medicine recommendations.

## 🚀 Features
- **Symptom-Based Medicine Suggestions** – Users input symptoms, and the system recommends suitable medicines.
- **Sentiment Analysis on Patient Reviews** – Analyzes reviews to determine medicine effectiveness.
- **Machine Learning Models** – Uses AI algorithms to predict the best medicine for a given symptom.
- **Data Scraping & Preprocessing** – Collects and cleans real-world patient reviews for accurate insights.
- **Flask API for Backend** – Provides REST APIs to interact with the recommendation system.
- **User-Friendly Interface** – A simple web UI for easy access to recommendations.

## 🛠️ Tech Stack
| Technology | Usage |
|------------|-------|
| **Frontend** | React.js / Flask Templates |
| **Backend** | Flask (Python) |
| **Database** | SQLite / PostgreSQL / MongoDB |
| **Machine Learning** | Python (scikit-learn, NLP, sentiment analysis) |
| **APIs** | Drug databases for real-time medicine information |

## 📂 Folder Structure
📦 Medicine-Recommendation-System ├── 📂 datasets # Contains input data (Excel/CSV) ├── 📂 models # Trained ML models (.pkl files) ├── 📂 static # CSS, images, and static assets ├── 📂 templates # HTML templates for Flask UI ├── 📜 main.py # Main Python script for Flask app ├── 📜 medications.xlsx # Medicine database ├── 📜 precautions_df.xlsx # Precautions dataset ├── 📜 svc.pkl # Saved ML model ├── 📜 README.md # Project documentation ├── 📜 requirements.txt # Dependencies for the project └── 📜 .gitignore # Files to ignore in Git

# ⚙️ Installation Guide
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/your-username/Medicine-Recommendation-System.git
cd Medicine-Recommendation-System

python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows
pip install -r requirements.txt


python main.py
