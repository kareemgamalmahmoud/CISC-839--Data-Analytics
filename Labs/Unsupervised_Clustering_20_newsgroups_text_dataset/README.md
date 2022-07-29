# Lab_3 : Unsupervised Learning (Advanced Clustering) 20 Newsgroups Text Dataset

- For this lab we will use Scikit-Learn’s API, sklearn.

- Datasets, which allows us to access a famous dataset for linguistic analysis, the 20newsgroups dataset.

- A newsgroup is an online user discussion group, such as a forum. Sklearn allows us to access different categories of content. We will use texts that have to do with technology, religion and sport.

- More details about the dataset: Link

- Your task is to perform clustering on the given dataset.

## Task 1:

- Read the dataset and report the basic statistics of the dataset.

- import data from sklearn.datasets and selecte pre-defined categories:

1) from sklearn.datasets import fetch_20newsgroups

2) categories = [ 'comp.graphics', 'comp.os.ms-windows.misc', 'rec.sport.baseball', 'rec.sport.hockey', 'alt.atheism', ]

3) dataset = fetch_20newsgroups(subset='train', categories=categories, shuffle=True, remove=('headers', 'footers', 'quotes'))

## Task 2: Data cleaning.

- Use standard text preprocessing steps to preprocess raw textual content.

- A sample preprocessing function is provided as below.

## Task 3:

- create vector representation of each document using TF-IDF encoding.

## Task 4:

- Apply Kmeans and Kmeans++ on the above extracted document vectors.

- Brifely describe how would you select the value of K.

## Task 6:

- compare the performance of the above four approaches on the given dataset using mutual information based scores
