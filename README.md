# Universal Genre Classification: Can Lyrics Alone Predict Music Genres?

**📌 Project Overview**

This project explores the possibility of classifying music genres based solely on song lyrics using Natural Language Processing (NLP) techniques. By managing a multilingual dataset and applying TF-IDF vectorization alongside classical machine learning models, we examine how well lyrics alone can determine genres such as rock, rap, and pop.

**📂 Dataset**

We used two datasets from Kaggle:
- Dataset 1: 4,000 songs (English-dominant)
- Dataset 2: 5 million songs (83 languages, filtered to rock, rap, and pop)

**🎼 Dataset Features**
- Title
- Artist
- Lyrics
- Genre
- Language

**⚙️ Methodology**

1️⃣ Preprocessing
- Tokenization & Lemmatization (using NLTK and spaCy)
- Language-based filtering (analyzed one language at a time)
- TF-IDF feature extraction to transform lyrics into numerical representations

2️⃣ Model Training
- We trained the following machine learning models using Scikit-learn:
- Random Forest 🌲
- Linear SVC 🏆
- Logistic Regression 📊 

3️⃣ Evaluation Metrics
- Accuracy
- Precision, Recall, F1-score
- Confusion Matrices

**📊 Results**

Rap is easiest to classify due to its unique vocabulary and structure.
Rock has high overlap with pop, making it harder to distinguish.
Multilingual models show performance variations based on linguistic complexity.

**🤝 Team**

 - Ajla Beća
 - Selma Salman
