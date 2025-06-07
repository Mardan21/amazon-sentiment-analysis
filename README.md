# Amazon Product Review Sentiment Classifier

This project uses traditional machine learning techniques to classify 34,000+ Amazon product reviews by sentiment (positive, neutral, negative). A complete pipeline was developed for preprocessing, feature engineering, SMOTE oversampling, and model evaluation. The final ensemble model balances performance across classes while avoiding the resource demands of deep learning.

---

## 🚀 Key Features
- Preprocessed raw text using lowercase, stopword removal, punctuation cleanup
- Engineered TF-IDF vectors (1-2 n-grams, top 5K features)
- Balanced dataset using SMOTE to overcome extreme class imbalance (93% positive)
- Trained and compared Logistic Regression, Naive Bayes, and SVM
- Final ensemble classifier achieved:
  - **Accuracy**: 84.5%
  - **Macro F1 Score**: 0.48
- Feature importance analysis revealed top indicators for each sentiment class

---

## 🛠 Tools & Technologies
- Python (Jupyter Notebook)
- scikit-learn
- imbalanced-learn (SMOTE)
- Text preprocessing (NLTK)
- TF-IDF vectorization
- Matplotlib, Seaborn

---

## 📄 Files
- `notebooks/amazon_review_sentiment.ipynb` 
- `report/amazon_review_sentiment_report.pdf` 

---

## 📈 Business Value
- Enables auto-tagging of reviews for customer triage
- Cuts review analysis time by 98% compared to manual processing
- Favors lightweight interpretable models over computationally expensive deep learning

---

## 📜 License
MIT (or your preferred license)
