🔍 Overview-

The objective of this project is to build an efficient text classification model that detects whether an incoming SMS or email message is Spam or Not Spam.
This helps prevent phishing, scams, and unwanted advertisements.

📂 Dataset-

Source: SMS Spam Collection Dataset

Size: 5,572 rows and 5 columns

🛠 Tools-

Language: Python

Libraries: pandas, numpy, nltk, scikit-learn, matplotlib, seaborn

Model: Multinomial Naive Bayes

Vectorization: TF-IDF

Deployment: Streamlit

Serialization: Pickle


📊 Project Workflow-

1)Data Cleaning

Removed unnecessary columns

Renamed columns (v1 → target, v2 → text)

Encoded labels (ham = 0, spam = 1)

Removed duplicates

2)Exploratory Data Analysis (EDA)

Distribution of spam vs ham

Message length analysis

Word and character frequency

3)Text Preprocessing

Lowercasing

Tokenization

Removing stopwords & punctuation

Stemming using Porter Stemmer

4)Feature Extraction

TF-IDF Vectorization (max_features = 3000)

5)Model Building

Multinomial Naive Bayes

Model Evaluation

Accuracy, Precision, Recall, F1-score

6)Deployment

Streamlit app
