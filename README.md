# IMDB Sentiment Analysis
In this project, a sentiment classifier is built which evaluates the polarity of a piece of text being either positive or negative. Given the availability of a large volume of online review data (IMDB), sentiment analysis becomes increasingly important. 


# IMDB Dataset

#### IMDB dataset has 50K movie reviews for natural language processing or Text analytics.
This is a dataset for binary sentiment classification containing substantially more data than previous benchmark datasets. We provide a set of 25,000 highly polar movie reviews for training and 25,000 for testing. So, predict the number of positive and negative reviews using either classification or deep learning algorithms.


# Data Preprocessing

The training dataset in aclImdb folder has two sub-directories pos/ for positive texts and neg/ for negative ones. Use only these two directories. The first task is to combine both of them to a single csv file, “imdb_tr.csv”. The csv file has three columns,"row_number" and “text” and “polarity”. The column “text” contains review texts from the aclImdb database and the column “polarity” consists of sentiment labels, 1 for positive and 0 for negative. The file imdb_tr.csv is an output of this preprocessing. In addition, common English stopwords should be removed. An English stopwords reference ('stopwords.en') is given in the code for reference.
