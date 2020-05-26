# Fake and Real News Predictor

Do you know the news you read today morning was a fake one or true ?
Can you find the difference between them ?

We here, try to solve this issue of fake news through the concepts of machine
learning by predicting if the content of information is real or fake.

#### Team Members : Avishi Goyal , Medha Gulati , Shivangi Mishra , Pooja Garg

The repositories include:
1. Code - separate repositories for each algorithm 
2. Data - Datasets and graph images 
3. Report - Overleaf Report 
4. Team Members - separate repositories for team members

## Link to Kaggle Dataset:
#### https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset

Number of instances:  17903 Fake News + 20826 True News

Number of attributes: 4

Whether labeled or unlabeled: labeled

Type of label information (if present): categorical


## Section 3.1: Fake News Dataset 
https://github.com/goyalavishi/Fake-and-Real-News-Predictor/blob/master/Data/Fake.csv

#### Fake News Preview :
![alt text](https://github.com/goyalavishi/Fake-and-Real-News-Predictor/blob/master/Data/fakenewspreview.png)

#### True News Preview :
![alt text](https://github.com/goyalavishi/Fake-and-Real-News-Predictor/blob/master/Data/truenewspreview.png)

#### Proposed Methodology :
![alt_text](https://github.com/goyalavishi/Fake-and-Real-News-Predictor/blob/master/Data/Images/ProposedMethodology.jpeg)

## Section 3.2: Data visualisation , Preprocessing can be found in file (preprocessing.ipynb)

#### Word Count Comparision In Title of News
![alt text](https://github.com/goyalavishi/Fake-and-Real-News-Predictor/blob/master/Code/WordCount/wl_news.png)

#### Word Count Comparision In Content of News
![alt text](https://github.com/goyalavishi/Fake-and-Real-News-Predictor/blob/master/Code/WordCount/wl_nt.png)

#### Stop Words Comparision In Title of News
![alt text](https://github.com/goyalavishi/Fake-and-Real-News-Predictor/blob/master/Code/WordCount/sw_nt.png)

#### Stop Words Comparision In Content of News
![alt text](https://github.com/goyalavishi/Fake-and-Real-News-Predictor/blob/master/Code/WordCount/sw_news.png)

### Tokenisation -> preprocessing.ipynb 
https://github.com/goyalavishi/Fake-and-Real-News-Predictor/blob/master/Code/DataPreProcessing/preprocessing.ipynb

### Sentimental Analysis -> SentimentalAnalysis.ipynb
https://github.com/goyalavishi/Fake-and-Real-News-Predictor/blob/master/Code/SentimentAnalysis/SentimentAnalysis.ipynb

#### Sentiments in Fake News 
![alt text](https://github.com/goyalavishi/Fake-and-Real-News-Predictor/blob/master/Data/Images/FakeNewsgraph.jpeg)

#### Sentiments in True News
![alt text](https://github.com/goyalavishi/Fake-and-Real-News-Predictor/blob/master/Data/Images/TrueNewsgraph.jpeg)

### Length of Characters -> news3.ipynb
https://github.com/goyalavishi/Fake-and-Real-News-Predictor/blob/master/Code/GrammarCheck/news3.ipynb

#### Length of Characters in a news
![alt text](https://github.com/goyalavishi/Fake-and-Real-News-Predictor/blob/master/Data/Images/LengthofChars.jpeg)


## Section 4.1.1: Multinomial NB and Random Forest can be found in file (XGB, RF, NB without stematization and Lemmatization.ipynb)
https://github.com/goyalavishi/Fake-and-Real-News-Predictor/blob/master/Code/NaiveBayes/XGB%2C%20RF%2C%20NB%20without%20stematization%20and%20Lemmatization.ipynb

## Final Result :
![alt text](https://github.com/goyalavishi/Fake-and-Real-News-Predictor/blob/master/Data/Images/FinalResult.jpeg)

