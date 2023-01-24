# InformationRetrieval

> Instructor: [Dr. A. Nikabadi](https://scholar.google.com/citations?user=pSMNSZwAAAAJ&hl=en)

> Course content: [CS276 Standford University](https://web.stanford.edu/class/cs276/)

> Semester: Fall 2022

This project is for Information Retrieval course which aims to implement a **<u>search engine</u>** for both phrase queries and Free text queries on [Fars News Dataset](https://drive.google.com/file/d/1x-ypTPZ0R_T83YfCw-p55MaQtpCvkrsb/view?usp=sharing). 

## First Phase

1. Preprocessing on data (Noramlization, Tokenization, Stemming, Removing Stopwords)

2. Working with both most used NLP persian toolkits : [hazm](https://github.com/roshan-research/hazm), [parsivar](https://github.com/ICTRC/Parsivar)

3. Created a positional inverted index

4. Used Zipf's law

<img src="https://github.com/rojinakashefi/InformationRetrieval/blob/main/pictures/zip2.png" title="" alt="zip2.png" width="238">

5. Used Heaps law

<img src="https://github.com/rojinakashefi/InformationRetrieval/blob/main/pictures/heaps.png" title="" alt="zip2.png" width="238">

6. Searching by Normal quries, Phrase Queries (used permuterm index), Boolean queries

7. Ranking results

## Second phase

1. Show words in vector representation

2. Compute tf-idf

3. Compute cosine similarity between query terms and documents

4. Used Index elimination techniques such as creating champion list 

5. Rank results based on most relevents

---

Contributors : Rojina kashefi & Leili Barekatein
