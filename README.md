PhishGuard AI (Backend Version)

🚀 Phishing Detection System using Machine Learning & Heuristics

📌 Overview

PhishGuard AI is a backend-based system that detects phishing URLs using heuristic analysis and a machine learning model. The system analyzes input URLs and provides a phishing prediction along with a risk score.

---

🎯 Objectives

- Detect phishing URLs using ML techniques
- Analyze URL-based features for threat detection
- Provide a risk scoring system
- Build a scalable backend security tool

---

🧠 Machine Learning Approach

- Model Used: (Write your model here: Logistic Regression / Decision Tree / etc.)
- Library: Scikit-learn

Features Used:

- URL Length (detects unusually long URLs)
- Suspicious Keywords (e.g., login, verify, bank)
- Special Character Frequency

Output:

- 1 → Phishing
- 0 → Safe

«Note: This model is a basic prototype and can be improved with larger real-world datasets.»

---

🛠️ Tech Stack

- Python
- Flask
- Scikit-learn

---

⚙️ How to Run

cd backend  
pip install -r requirements.txt  
python app.py  

---

📡 API Usage

Endpoint

POST /predict

Input (JSON)

{
  "url": "http://example.com"
}

Output (JSON)

{
  "prediction": "Phishing",
  "risk_score": 0.82
}

---

📊 Future Scope

- Training with real phishing datasets (e.g., Kaggle)
- Integration with WHOIS and SSL verification
- Improved ML model accuracy
- Deployment as a cloud-based API

---

📌 Conclusion

PhishGuard AI demonstrates how machine learning and heuristic techniques can be combined to detect phishing attempts. It serves as a foundational project that can be further enhanced into a real-world cybersecurity solution.
