# emotion detection using NLP
this project is a text classification system that detects emptions(haapy,natural,sad..etc) using NLP and ML

## Overview
- This project implements a text classification system that automatically detects emotions in text. Emotion detection is useful in:
- Customer feedback analysis
- Social media monitoring
- Chatbots & virtual assistants
- Mental health applications
The system leverages NLP preprocessing, TF-IDF vectorization, and a machine learning classifier to predict emotions with high accuracy.

## Preprocessing
- Cleaned and lemmatized text using spaCy
- Removed stopwords, punctuation, and special characters
- Converted text into numerical vectors with TfidfVectorizer
  
## Model Training
- Trained a machine learning classifier (e.g., Logistic Regression / SVM / Naive Bayes – whichever you used)
- Hyperparameter tuning with cross-validation
 - Evaluated using classification report (precision, recall, F1-score)

## Results
- Training Accuracy: 98%
- Test Accuracy: 93%
- Average Cross-Validation Score: 94%

  ## Usage
 1.  Clone the repository and install dependencies:
```bash
git clone https://github.com/zaralrubaie/emotion-detection-nlp.git
cd emotion-detection-nlp
pip install -r requirements.txt
```
2. Run preprocessing & training:
```bash
python src/train.py
```
## Technologies Used

- Python
- spaCy
- Scikit-learn
- Pandas, NumPy
- Matplotlib / Seaborn (for evaluation & visualization)



