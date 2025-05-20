# HealthInsight: AI-Based Diagnostic Support System

HealthInsight is a full-stack project designed to assist doctors and patients in identifying potential illnesses based on symptoms and blood test results. The system uses machine learning to suggest likely conditions and provides interpretable outputs.

# 🚀 Features

Input patient symptoms and blood test data

Predict top 5 possible conditions with confidence scores

Built-in explainability support (planned)

Designed for primary care and telemedicine applications

# 🖥️ Tech Stack

Layer

Tech

Frontend

React + Tailwind CSS

Backend

FastAPI (Python)

ML

scikit-learn, RandomForest

Storage

In-memory / JSON (for MVP)

# 📂 Project Structure

medpredict/
├── frontend/                  # React UI
│   └── HealthInsightForm.jsx
├── backend/                   # FastAPI server
│   └── main.py
├── model/                     # ML model and training
│   ├── train_model.py
│   └── model.pkl
├── README.md
└── requirements.txt

# ⚙️ Installation & Running

1. Clone the Repository

git clone https://github.com/yourusername/HealthInsight.git
cd HealthInsight

2. Set up the Backend (FastAPI)

cd backend
pip install -r requirements.txt
python main.py

3. Train the ML Model

cd model
python train_model.py

4. Start the Frontend (React)

cd frontend
npm install
npm run dev

# 🔍 Example Usage

Input:

Symptoms: fatigue, shortness of breath

Blood Test: Hemoglobin: 11.2, WBC: 8.0

Output:

[
  { "condition": "Anemia", "confidence": 85.2 },
  { "condition": "Infection", "confidence": 45.3 }
]

# 🧠 Future Enhancements

Integrate SHAP for interpretability

Connect to FHIR-compatible EHRs

Support CSV/PDF parsing for lab reports

HIPAA/GDPR-compliant deployment

# 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first.

# 📄 License

MIT License

# 📬 Contact

Built by [Your Name]Email: [your@email.com]LinkedIn: [linkedin.com/in/yourname]
