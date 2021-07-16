### assgn7-Embeddings

Encoding techniques , such as OHE , works well for categorical scenarios but for free text it will lead to really sparse and huge matrix which is difficult & inefficient to handle and inappropriate for the tasks ahead . Thus we resort to Embedding techniques which help convert Text into Numerical representation while maintaing underlying semantics of the text and keeping the matrix concise. 

On the the preprocessed text data created from 10 text documents in previous assignment , apply the following elementary Embedding techniques on the 10 documents. 

1. Bag of Words
2. Term Frequency Inverse Document Frequency (TF-IDF)

Refer the following articles , understanding the context around these and their limitations and eventually apply them :

Background : https://www.analyticsvidhya.com/blog/2020/02/quick-introduction-bag-of-words-bow-tf-idf/

Bag of Words : https://blog.quantinsti.com/bag-of-words/

Scikit Implementation : 

https://scikit-learn.org/stable/modules/feature_extraction.html
https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html


---------------

Timeline Jul 16th , 5 PM
   
