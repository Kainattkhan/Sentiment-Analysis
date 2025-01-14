# 🛍️ Amazon Reviews Sentiment Analysis  

This project analyzes Amazon product reviews using **Logistic Regression** and **Linear Regression** for sentiment classification. It includes **data preprocessing, model training, and evaluation** with visualization.  

## 📂 Dataset  
**Source:** `/kaggle/input/amazon-reviews/Reviews.csv`  
**Key Columns:**  
- `Text` (Review content)  
- `Score` (Sentiment label: 1-5 stars)  

## 🔍 Steps  
1️⃣ **Data Preprocessing:**  
- Clean text (remove stopwords, punctuation)  
- Convert ratings into **binary sentiment** (positive/negative)  
- Vectorize text using **TF-IDF**  

2️⃣ **Model Training & Evaluation:**  
- **Logistic Regression**    
- **Metrics:** Accuracy, Confusion Matrix, Precision-Recall Curve  

3️⃣ **Visualization:**  
- Confusion Matrix  
- Precision-Recall Curve  

## 🚀 How to Run  
```python
# Install dependencies
pip install pandas scikit-learn matplotlib seaborn

# Run the notebook
Kaggle notebook
```

## 📊 Results  
- **Logistic Regression** performed well with good precision & recall.  
