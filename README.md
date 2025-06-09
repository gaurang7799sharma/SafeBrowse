🔐 SafeBrowse: Feature-Driven Identification of Phishing Websites
SafeBrowse is a machine learning-based web application that detects phishing websites in real-time by analyzing key features extracted from URLs and associated metadata. Built using Python, Flask, and XGBoost, this project offers a scalable and lightweight solution for cybersecurity applications such as browser extensions, email filters, or secure payment gateways.

🚀 Features
✅ Real-time phishing detection using a pre-trained XGBoost model (95.18% accuracy)

🔍 Extracts 88+ handcrafted lexical, domain-based, and content-based features

⚙️ Implements Recursive Feature Elimination (RFE) for feature selection

🌐 Flask-powered web interface for easy user interaction

🧠 Comparative analysis using Decision Tree, SVM, Naive Bayes, and Random Forest

📁 Dataset
Total URLs: 11,430 (Balanced – 50% phishing, 50% legitimate)

Source: Structured CSV with URL features like domain_age, web_traffic, google_index, etc.

🧪 Models Compared
XGBoost (Best Performer – 95.18% accuracy)

Random Forest

Decision Tree

SVM

Naive Bayes

Logistic Regression

📈 Evaluation Metrics
Accuracy, Precision, Recall, F1-score (validated via 5-fold cross-validation)

🛠 Technologies Used
Python (NumPy, Pandas, Scikit-learn, XGBoost)

Flask (for deployment)

Joblib (model serialization)

📌 How it works
User inputs a URL via the Flask web app

Feature extraction is triggered

The pre-trained XGBoost model classifies the URL

Result is instantly displayed as Phishing or Legitimate

📚 Research Publication
Presented at: 4th International Conference on Networks and Cryptology, New Delhi, India
Status: Communicated
Authors: Aman Yadav & Gaurang Shekhar Sharma (gaurangsharma752@gmail.com, 7668677441 for any queries regarding working of the project Whatsapp)
Supervisor: Mr. Arnav Kotiyal (Graphic Era University)
