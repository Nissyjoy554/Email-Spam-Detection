📧 Email Spam Detection (Classification)
🧠 Overview

This project uses Machine Learning techniques to classify emails as Spam or Not Spam based on their text content.
It applies Natural Language Processing (NLP) and a Logistic Regression model to identify spam messages efficiently.# Email-Spam-Detection
Machine Learning project for detecting spam emails using NLP and Logistic Regression

///

🧩 Features

Preprocesses email text using TF-IDF Vectorization

Trains a Logistic Regression classifier

Evaluates with Accuracy, Confusion Matrix, and Classification Report

Predicts custom sample messages for real-world testing

///

🛠️ Technologies Used

~ Python

~ NumPy, Pandas

~ Matplotlib, Seaborn

~ Scikit-learn

~ Natural Language Processing (TF-IDF)

///

⚙️ Steps Performed

Data Loading & Cleaning

Label Encoding (ham → 0, spam → 1)

Train-Test Split

////

📊 **Model Evaluation**
Metric	Score
Accuracy	~97%
Precision	0.96
Recall	0.86
F1-Score	0.91

TF-IDF Vectorization
Model Training (Logistic Regression)
Evaluation Metrics
Prediction on Sample Emails

🔮 **Example Predictions**
Email Message	                                                 Prediction
“Congratulations! You’ve won a $1000 Walmart gift card.”	        Spam
“Hey, are we still meeting for lunch today?”              	    Not Spam
“Urgent! Your account has been compromised.”	                    Spam


🚀 **How to Run**

1. Open in Google Colab

2. Copy the provided code into a new notebook

3. Run all cells

4. Test with your own messages in the “Sample Predictions” section
