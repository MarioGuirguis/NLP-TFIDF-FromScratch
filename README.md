# NLP-TFIDF-FromScratch
This Project generates documents and implement TFIDF from scratch on it.
<br/>
# The Code follows this steps:
## Data:
Generate 3 documents using 'gpt2' model in python.
## Preproccessing:
1. Lemmatization: return each word to origin.
2. Data Normalization: Make all the data to lower case.
3. Cleaning data from [HTML Tags, Links and Emails, Symbols, Numbers, Emojis, Non-Ascii charachters].
4. Spell Correction.
5. Remove Stop Words.
6. Tokenization: split the data to words.
## Unique Words:
Get Unique words after splitting the data to words by using python Set Data Structure.
## TF-IDF:
1. Get TF for each word for all documents.
2. Get IDF for each word.
3. Multiply TF * IDF
4. Get Normalized TFIDF
5. Compare with built-in TFIDF
<br/>
# Libraries to Import:
- pip install BeautifulSoup
- pip install pyspellchecker
- pip install nltk
- nltk.download('stopwords')
- pip install -U scikit-learn
- pip install -U spacy
- pip install pandas
- pip install numpy
- pip install transformers
