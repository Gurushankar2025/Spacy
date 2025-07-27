# spaCy NLP Exercises Portfolio

This repository contains beginner to intermediate **spaCy** exercises covering core NLP tasks.  
It demonstrates practical text processing skills, including tokenization, stopword handling, NER, POS tagging, and frequency analysis.

---

## **Contents**

### 1. Tokenization & Customization
- Default tokenization
- Custom infix rules (handle dots in `Dr.Strange`, `U.S.A.`)

### 2. Named Entity Recognition (NER)
- Entity extraction from paragraphs
- Understanding entity types (PERSON, ORG, GPE, DATE)

### 3. POS Tagging & Dependency Visualization
- POS tag extraction
- Dependency tree visualization with `displacy`

### 4. Stopword Handling & Frequency Count
- Remove stopwords and compare original vs cleaned text
- Frequency count of words using:
  - **Goose3** for text cleaning
  - **collections.Counter** for word frequency analysis

### 5. Lemmatization
- Lemmatize text and compare original vs lemmatized output

### 6. Word Similarity
- Similarity scores between words and simple sentences

---

## **Technologies Used**
- **spaCy** (en_core_web_sm / md)
- **Python** (Counter, regex)
- **Goose3** (for optional text cleaning)
- Google Colab (development environment)

---

## **How to Run**
1. Clone this repo or open a notebook in Colab
2. Install dependencies:
   ```bash
   pip install spacy goose3
   python -m spacy download en_core_web_sm
