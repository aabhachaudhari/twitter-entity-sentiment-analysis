# 💬 Social Media Sentiment Analysis (Twitter Entity Dataset)

This project analyzes and visualizes **sentiment patterns in social media data** to understand public opinion and attitudes toward specific topics or brands. The focus is on building a clean NLP pipeline, performing EDA, and visualizing sentiment trends using the Kaggle Twitter Entity Sentiment dataset.

---

## 🔎 What I did (Quick Overview)
- Cleaned and preprocessed raw tweet text  
- Performed **EDA** to explore sentiment distribution across entities  
- Built a baseline **sentiment classification** model  
- Visualized sentiment patterns for selected topics/brands  
- Interpreted results to understand public opinion trends  

---

## 🧠 Approach
- Text preprocessing: lowercasing, removing URLs/mentions, tokenization  
- Handled noisy social media text and class imbalance  
- Converted text to features (TF-IDF / basic embeddings)  
- Trained a baseline classifier (e.g., Logistic Regression / Naive Bayes)  
- Evaluated using **accuracy, precision, recall, F1-score**  
- Visualized sentiment counts and trends by entity  

---

## 📈 Key Observations
- Sentiment distribution varies significantly across entities/brands  
- Neutral sentiment dominates, with clear positive/negative clusters for certain topics  
- Simple text preprocessing improves baseline model performance  
- Visualization helps quickly identify **entities with polarized opinions**

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- scikit-learn  
- NLTK / spaCy (for text preprocessing)  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## 📂 Dataset
Kaggle – Twitter Entity Sentiment Analysis  
https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis  

Public dataset used for NLP practice and sentiment analysis.

---

## 🚀 How to Run
1. Clone the repository  
2. Install dependencies
3. Open the notebook
4. Run all cells to preprocess text, train the model, and visualize results  

---

## 🎯 Learning Outcomes
- Built a basic **NLP preprocessing pipeline** for noisy social media text  
- Performed **EDA on text + sentiment labels**  
- Trained and evaluated a **baseline sentiment classifier**  
- Learned to interpret and visualize **public opinion trends**  

---

## ⚠️ Notes
This is a learning project focused on exploratory analysis and a baseline ML model. Results depend on preprocessing choices and class balance.

---

## 🔮 Future Improvements
- Try advanced models (SVM, XGBoost, BERT)  
- Improve preprocessing (lemmatization, handling emojis)  
- Add time-based sentiment trends  
- Perform topic modeling for deeper insights  
