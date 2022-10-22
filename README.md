# NLP-projects
All projects which are related to NLP and web scraping!

General Description:
-----------------------
In this repository, you can see my nlp researche. Every folder contains a specific topic. In the following, I will give a concise explanation of every project:


Quotes:
--------
Data source: https://www.goodreads.com/quotes/tag/science?page=1

This folder has two sub-folders:
- Web scrapping: I scrapped the mentioned site to extract quotes from famous figures. This data consists of text (quote), tags ,and the number of likes from pages 1 to 50. Note that the site has arranged quotes according to their popularity (likes)
- insight: By virtue of the above data, I pulled out some important aspects of the text (word cloud, number of repetitions, ..)

Luther King's speech:
----------------------
Data source: https://www.npr.org/2010/01/18/122701268/i-have-a-dream-speech-in-its-entirety

This folder has just one notebook. Firstly, I extracted the King's speech (called 'I have a dream') and then, perform some language-related processes.


Medical_text:
--------------
Data source: https://www.kaggle.com/datasets/falgunipatel19/biomedical-text-publication-classification

As an introduction to data, I quote from its data source: "for Biomedical text document classification, abstract and full papers(whose length less than or equal to 6 pages) available and used. This dataset focused on long research paper whose page size more than 6 pages. Dataset includes cancer documents to be classified into 3 categories like 'ThyroidCancer','ColonCancer','Lung_Cancer' ". In this folder, I have performed a preprocessing to clean text data and then classificaton of them (with a high precission) using SVM and Naive Bayes.

