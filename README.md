# 🧠 Text Representation Techniques in NLP

## 📌 Project Overview
This project explores fundamental text representation techniques in Natural Language Processing (NLP). It demonstrates how raw textual data can be transformed into numerical formats using classical and modern methods such as Bag of Words (BoW), TF-IDF, N-grams, and Word2Vec.

The goal is to understand how different representations capture linguistic patterns and semantic relationships.

---

## 🚀 Key Features / Concepts
- Text preprocessing (lowercasing, removing punctuation, stopwords removal)
- Bag of Words (BoW) representation
- TF-IDF (Term Frequency – Inverse Document Frequency)
- N-gram models (Unigram, Bigram, Trigram)
- Word2Vec embedding model (Gensim)
- Word similarity and analogy queries
- t-SNE visualization of word embeddings
- Frequency-based analysis and visualization

---

## 🛠 Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK
- Gensim

---

## 🔄 Workflow

### 1. Data Preparation
- Created a small labeled text dataset
- Separated text and labels

### 2. Text Preprocessing
- Converted text to lowercase
- Removed numbers and special characters
- Removed stopwords using NLTK
- Cleaned text for modeling

### 3. Bag of Words (BoW)
- Used `CountVectorizer`
- Converted text into frequency-based vectors
- Analyzed most frequent words
- Visualized top word frequencies

### 4. TF-IDF Representation
- Applied `TfidfVectorizer`
- Calculated importance of words across documents
- Identified highest weighted terms

### 5. N-gram Modeling
- Generated:
  - Unigrams
  - Bigrams
  - Trigrams
- Observed how context improves with n-gram size

### 6. Word2Vec Embedding
- Tokenized sentences using `simple_preprocess`
- Trained Word2Vec model
- Extracted word vectors
- Found similar words
- Performed analogy queries

### 7. Visualization
- Reduced word vectors using t-SNE
- Visualized semantic relationships between words

---

## 📊 Results
- BoW highlighted high-frequency terms but lacked semantic meaning
- TF-IDF emphasized more informative words (e.g., "new")
- N-grams captured contextual relationships between words
- Word2Vec successfully learned semantic similarities and analogies
- t-SNE visualization demonstrated clustering of related words

---

## ▶️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/Leman2006/text-representation-nlp.git

