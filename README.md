🛡️ FraudShield AI
AI-Powered Credit Card Fraud Detection & Credit Card Approval System
FraudShield AI is a modern banking security platform that combines Machine Learning and Web Technologies to detect fraudulent credit card transactions and evaluate credit card applications. The application is built using Python, Flask, MySQL, Pandas, Scikit-Learn, HTML5, CSS3, and JavaScript.

📌 Features
💳 Credit Card Approval System
Customer application form
PAN number validation (automatic uppercase formatting)
Annual income verification
Credit score evaluation
Employment status
Existing loan information
Requested credit limit
Bank statement upload (PDF, CSV, XLSX)
Instant approval or rejection
Application data stored in MySQL
🤖 Machine Learning Fraud Detection
The fraud detection module is powered by a Random Forest Classifier trained on the Kaggle Credit Card Fraud Detection Dataset.

Input Features
Transaction Time
Transaction Amount
Output
Normal Transaction
Fraud Transaction
Prediction Confidence Score
Model Information
Algorithm: Random Forest Classifier
Training Dataset: Kaggle Credit Card Fraud Detection
Total Records: 284,807
Fraud Transactions: 492
Model Accuracy: 99.81%
📊 Analytics Dashboard
Interactive banking dashboard displaying:

Total Transactions
Fraud Transactions
Normal Transactions
Fraud Rate
Credit Card Applications
Approved Applications
Rejected Applications
Model Accuracy
Banking Statistics
Pie Charts
Performance Cards
Live Banking Activity
📂 Dataset Upload
Users can upload transaction datasets to perform quick analysis.

Supported formats:

CSV
Excel (.xlsx)
PDF Bank Statements
The application automatically displays:

Total Transactions
Fraud Transactions
Normal Transactions
💻 Technology Stack
Frontend
HTML5
CSS3
JavaScript
Google Fonts (Outfit)
Backend
Python
Flask
Database
MySQL
Machine Learning
Scikit-Learn
Random Forest Classifier
Joblib
Libraries
Pandas
NumPy
MySQL Connector
📁 Project Structure
FraudShieldAI/
│
├── app.py
├── train_model.py
├── requirements.txt
├── README.md
│
├── templates/
│   ├── dashboard.html
│   ├── analytics.html
│   ├── approval.html
│   ├── result.html
│   ├── predict.html
│   ├── upload.html
│   └── about.html
│
├── datasets/
│   └── creditcard.csv
│
├── trained_models/
│   └── fraud_model.pkl
│
├── uploads/
│
└── static/
🗄 Database
Database
fraudshield
Table
applications
Stored Information
Applicant Name
Age
PAN Number
Annual Income
Credit Score
Employment Status
Existing Loan
Requested Credit Limit
Approval Status
🚀 Installation
Clone Repository
git clone https://github.com/sai-1435/FraudShieldAI.git
Move to Project
cd FraudShieldAI
Install Dependencies
pip install -r requirements.txt
Train the Machine Learning Model
python train_model.py
Start Flask Server
python app.py
Open your browser:

http://127.0.0.1:5000
🧠 Machine Learning Workflow
creditcard.csv
        │
        ▼
Data Preprocessing
        │
        ▼
Random Forest Training
        │
        ▼
fraud_model.pkl
        │
        ▼
Flask Web Application
        │
        ▼
Fraud Prediction
🔒 Security Features
Secure Credit Card Application Processing
PAN Number Validation
Bank Statement Upload
Machine Learning Fraud Detection
Confidence Score Prediction
Credit Score Evaluation
MySQL Database Storage
📈 Future Enhancements
User Authentication
Admin Dashboard
OTP Verification
PAN API Verification
Aadhaar Verification
Email Notifications
SMS Alerts
Banking API Integration
Real-Time Fraud Monitoring
Advanced Deep Learning Models
Explainable AI (XAI)
👨‍💻 Developer
Dasari siva sai venkateswara rao

B.Tech – Computer Science & Engineering

Academic Project – 2026

📜 License
This project is developed for educational and academic purposes only.
