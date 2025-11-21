# 📝 Amazon Product Review Sentiment Analysis (NLP + Machine Learning)

This project is an end-to-end sentiment classification model built on Amazon product reviews.  

---

## Project Objective
To classify Amazon product reviews as **positive, negative, or neutral** using a combination of:
- Text preprocessing  
- TF-IDF vectorization  
- Machine learning classification algorithms  

This project demonstrates my understanding of practical NLP workflows used in real AI/ML systems.

---

## Dataset
A sample dataset containing customer reviews and sentiment labels is included.  
It represents typical real-world challenges:
- Noisy text  
- Mixed sentiments  
- Unstructured user-generated content  

---

## End-to-End Workflow

### **1. Data Understanding**
- Loading structured + unstructured data  
- Class distribution analysis  
- Identifying noise and inconsistencies  

### **2. Text Preprocessing (NLP Pipeline)**
- Converting text to lowercase  
- Removing punctuation & special symbols  
- Removing stopwords  
- Tokenization  
- Lemmatization  
This step improves signal quality before feature extraction.

### **3. Feature Engineering**
Using **TF-IDF Vectorizer** to create numerical representations of text.  
This enables even simple models to learn meaningful patterns in language.

### **4. Model Building**
Trained traditional ML models such as:  
- Logistic Regression  
- Naive Bayes  

These models work well for small/medium NLP tasks and offer interpretability.

### **5. Evaluation**
- Accuracy score  
- Confusion matrix  
- Classification report  
- Error analysis  
This ensures the model’s predictions are reliable.

---

## Project Structure
├── Amazon_Sentiment_Analysis.ipynb
├── sample_reviews.csv
└── README.md

---

##Technologies & Skills Demonstrated

### **Languages & Libraries**
- Python  
- Pandas, NumPy  
- Scikit-Learn  
- NLTK / spaCy  
- Matplotlib / Seaborn  
- Google Colab  

### **Core Skills**
- Natural Language Processing  
- Data Cleaning & Preprocessing  
- Feature Engineering  
- Model Selection & Evaluation  
- Analytical Storytelling  
- Reproducible ML Workflow  

---

##How to Run
1. Clone the repository  
2. Install Python dependencies  
3. Launch Jupyter Notebook  
4. Run all cells in order
