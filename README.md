# Sentiment Analysis on Apple Pay | ML vs DL

## Project Overview
This project aims to classify user sentiment toward Apple Pay services based on over 240,000 user comments. Both traditional Machine Learning and Deep Learning models were applied and compared.

## Tools & Libraries
- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Scikit-learn
- TensorFlow / Keras

## 📊 Dataset
- Total comments: ~241,000
- Sentiment labels: 
  - 0 = Negative  
  - 1 = Neutral  
  - 2 = Positive  

## Workflow
1. *Data Cleaning & Preprocessing*
   - Removed null values and irrelevant columns.
2. *Feature Engineering*
   - TF-IDF vectorization for ML models.
   - Tokenization & Padding for DL models.
3. *Model Training*
   - ML: Logistic Regression, Naive Bayes, KNN, Random Forest
   - DL: LSTM, GRU
4. *Evaluation*
   - Accuracy score
   - Confusion Matrix
   - Comparison Barplot

## Results
- *Best ML Model:* Random Forest (Accuracy: 83%)
- *Best DL Models:* LSTM & GRU (Accuracy: 85%)
- Deep learning models slightly outperformed traditional models in this dataset.

## Author
*Abdulaziz Mohammed Al-Garni*
