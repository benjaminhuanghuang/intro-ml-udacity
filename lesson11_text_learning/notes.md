# Lession 11: Text Learning

- Bag of words: Frequency count of words




## Quiz: Properties of Bag of Words
- Does the word order matter?  NO
- Do long phrase give different input vector?  YES
- Can we handle comples phrases?  NO


## Bag of words in sklearn
- CountVecotrizer
```
    from sklearn.feature_extraction.text import CountVectorizer
    vecotrizer = CountVecotrizer()
    s1 = ''
    s2 = ''
    email_list = [s1, s2]
    bag_of_words = vectorizer.fit(email_list)
    bag_of_words = vectorizer.transform(email_list)  
     
```

## Stop words
- low information words

## Stemmer
```
    from nltk.stem.snowball import SnowballStemmer
```
Stemming before bag-of-words

## TfIdf
- Tf: Term frequency, like bag of words
- Idf: Inverse document frequency, weighting by how often word occursin corpus
