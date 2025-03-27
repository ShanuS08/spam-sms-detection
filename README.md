# Spam SMS Detection

## Objective  
This project aims to develop a machine learning model that classifies SMS messages as either **spam** or **ham (legitimate)** using **Natural Language Processing (NLP) techniques** and **machine learning algorithms**.  

## Dataset  
The dataset consists of **5,574 SMS messages**, labeled as **spam** or **ham**. Each row in the dataset contains:  
- **v1 (label)** → `ham` (legitimate message) or `spam` (unwanted message)  
- **v2 (text)** → SMS content  

## Technologies Used  
- Python  
- Pandas  
- NLTK (Natural Language Toolkit)  
- Scikit-Learn  
- TfidfVectorizer  
- Naive Bayes Classifier  
- Random Forest Classifier  

## How It Works  
1. **Load the dataset**  
2. **Preprocess text**  
   - Convert to lowercase  
   - Remove punctuation  
   - Remove stopwords  
3. **Convert text to numerical features** using `TfidfVectorizer`  
4. **Train models** using `Multinomial Naïve Bayes` and `Random Forest`  
5. **Evaluate the model** on test data   

## Model Performance  
- **Naïve Bayes Accuracy**: ~97%  
- **Random Forest Accuracy**: ~98%  
