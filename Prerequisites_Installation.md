# Prerequisites and Installation
This course uses **Python-based NLP libraries** for live demonstrations and hands-on exercises.  
Students are **not required to install heavy frameworks initially**; most exercises can be run using **Google Colab**.

---

## Recommended Environment

### Option 1: Google Colab (Strongly Recommended)
Google Colab provides a zero-setup environment and will be used during live lectures.

- No local installation required
- Runs in the browser
- Supports all libraries used in this course

### Option 2: Local Setup (Optional)

Students who prefer a local setup should have the following installed:

- Python **3.9 or above**
- `pip` package manager
- Jupyter Notebook or JupyterLab
---
## Tools and Libraries Used

The following tools will be used throughout the course:

- **spaCy**  
  For tokenization, sentence segmentation, POS tagging, and Named Entity Recognition (NER)

- **NLTK**  
  For classic NLP utilities such as stemming and baseline tokenization

- **scikit-learn**  
  For feature extraction (Bag-of-Words, TF-IDF, n-grams) and traditional ML pipelines

- **Jupyter Notebook / Google Colab**  
  For interactive, live execution of code during lectures

- **Hugging Face Transformers**  
  For demonstrating modern NLP tokenization and representation methods, including:
  - Subword tokenizers (WordPiece, BPE, SentencePiece)
  - Model-specific tokenization using `AutoTokenizer`
  - Understanding differences between classic NLP pipelines and transformer-based workflows  

  Transformers will be introduced **conceptually and incrementally**, focusing on how tokenization and embeddings differ from traditional NLP preprocessing.

- **Jupyter Notebook / Google Colab**  
  For interactive, live execution of code during lectures
---

## Task-wise Installation Guide
Different NLP tasks in this course require different libraries.  
Students are advised to install **only what is required** for the task being demonstrated.

### 1. Tokenization, Sentence Segmentation, POS Tagging, NER
Used for:
- Word and sentence tokenization
- Part-of-Speech (POS) tagging
- Named Entity Recognition (NER)

Required libraries:
```bash
pip install spacy
python -m spacy download en_core_web_sm
```

### 2. Classic NLP Preprocessing (Stopwords, Stemming, Lemmatization)

Used for:
- Stop word removal
- Stemming (e.g., Porter Stemmer)
- Lemmatization comparison

Required libraries:
```bash
pip install nltk
```
**Verify:**
```bash
import nltk
nltk.download("punkt")
```
### 3. Feature Extraction (Bag-of-Words, TF-IDF, n-grams)

Used for:
- Converting text into numerical features
- Traditional machine learning pipelines

Required libraries:
```bash
pip install scikit-learn
```

### 4. Transformer-based Tokenization (Modern NLP)

Used for:
- Subword tokenization (WordPiece, BPE, SentencePiece)
- Demonstrating `AutoTokenizer`
- Comparing classic NLP vs transformer-based workflows

Required libraries:
```bash
pip install transformers sentencepiece
```
---

## Notes on Usage

- Students are encouraged to run notebooks during lectures
- All examples are designed to be modifiable and exploratory
- Installation steps may be updated incrementally as new topics are introduced

