# 📌 Fake News Detection
# 📖 Overview

Fake news has become increasingly widespread on social media, influencing public opinion and spreading misinformation.
This project aims to detect fake news using Machine Learning and Deep Learning models.

# ⚙️ Tech Stack
Python
Pandas, NumPy
Scikit-learn
TensorFlow / Keras
Matplotlib / Seaborn

# 🧹 Data Cleaning
Converted text to lowercase
Removed URLs, punctuation, and extra spaces
Handled and dropped missing values

# 📊 Exploratory Data Analysis (EDA)
Checked class distribution (dataset was balanced)
Analyzed number of words, characters, and sentences
Compared sentiment distribution between real and fake news
Extracted top words using bar charts
Performed bigram and trigram analysis
Visualized punctuation usage

# 🔄 Data Preprocessing
Tokenization
Stopword removal
Non-alphabetic token filtering
Lemmatization

# 🧠 Feature Engineering
Combined title + text to improve model understanding

# ✂️ Train-Test Split
Split data into training and testing sets before feature extraction to prevent data leakage

# 🔢 Feature Extraction (TF-IDF)

Fitted TF-IDF on training data only
Transformed both training and test sets

# 🤖 Modeling
Machine Learning Models:
Naive Bayes
Support Vector Machine (SVM)
Random Forest
Deep Learning Models:
CNN
LSTM

Text sequences were prepared using tokenization and padding

# results 
📈 Results
Achieved 0.99 F1-score using:
SVM
CNN
