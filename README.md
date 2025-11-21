# 📝 Amazon Product Review Sentiment Analysis
This project performs sentiment analysis on Amazon product reviews to classify them into **positive**, **negative**, or **neutral** sentiments.  
The goal is to understand customer opinions and extract insights from text reviews using standard NLP preprocessing techniques and machine learning models.

---

##Dataset
The dataset contains Amazon product reviews with corresponding sentiment labels  
(positive / negative / neutral).  
A small sample dataset is included in this repository for demonstration.

---

## Steps Performed
###1. Data Loading & Exploration
- Importing the dataset
- Checking missing values  
- Reviewing class distribution  

###2. Text Cleaning & Preprocessing
- Lowercasing  
- Removing punctuation  
- Removing stopwords  
- Lemmatization / stemming  
- Tokenization  

###3. Feature Extraction
- Converting text into numerical features using **TF-IDF Vectorizer**

###4. Model Training
- Training a simple machine learning classifier (e.g., Logistic Regression / Naive Bayes)
- Splitting dataset into train & test sets  

### 5. Model Evaluation
- Accuracy  
- Confusion matrix  
- Classification report  

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-Learn  
- NLTK / spaCy  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## Project Structure
├── Amazon_Sentiment_Analysis.ipynb
├── sample_reviews.csv
└── README.md

## How to Run
1. Clone the repository  
2. Install the required libraries  
3. Open the notebook in Jupyter  
4. Run the cells sequentially
