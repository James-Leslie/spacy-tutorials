# spacy-tutorials

Re-usable code snippets for general NLP tasks using spaCy

> Install environment for this repository using 
```
conda create --name spacy --file spec-file.txt
```

## Table of contents
  1) **[Basics](https://github.com/James-Leslie/spacy-tutorials/blob/master/0_basics.ipynb)**  
    1) Tokenization  
    2) Parts-of-speech tagging  
    3) Entity detection  
    4) Dependency parsing  
    5) Word vectors  
    6) Similarity  
  2) **[Text classification](https://github.com/James-Leslie/spacy-tutorials/blob/master/1_text_classification.ipynb)**  
    1.1) TFIDF transformer with custom spaCy tokenizer  
    1.2) scikit-Learn pipeline document classifier  
    2) Document vector classifier
  3) **[Document similarity](https://github.com/James-Leslie/spacy-tutorials/blob/master/2_document_similarity.ipynb)**   
    1) TFIDF transformer > cosine similarity nearest neighbours  
    2) Document vector transformer > nearest neighbours

---
### Download spaCy language model
Before running any of these notebooks, make sure to download the spaCy English language model using the following command:
```bash
python -m spacy download en_core_web_md
```
