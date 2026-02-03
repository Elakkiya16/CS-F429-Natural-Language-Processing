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

For Colab-based notebooks, run the following **once at the top of each notebook**:

```bash
!pip -q install spacy nltk scikit-learn
!python -m spacy download en_core_web_sm -q
```
