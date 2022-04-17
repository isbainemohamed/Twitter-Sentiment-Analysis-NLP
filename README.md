# Twitter-Sentiment-Analysis Project:  [get the dataset here:](https://drive.google.com/file/d/19IeqXU96-kDt6wy1wTNyhWrIw1jbK2Kx/view) 

**This Project has been done by : [ISBAINE MOHAMED](https://www.kaggle.com/mohamedisbaine) & [LABRIJI SAAD](https://www.kaggle.com/saadlabriji)**

## Introduction:

In social networks, twitter for example, is the 
ideal place for anyone to post their ideas and 
thoughts, but to avoid the spread of hateful 
tweets, it is absolutely necessary to have an 
automated system capable of detecting the 
nature of the feelings behind a text. To solve 
this kind of problem, we thought my 
teammate and I that we could use the modest 
knowledge we acquired in data science courses 
this year, to develop an Automated Machine 
Learning Sentiment Analysis Model in order 
to compute the customer perception.
In Our days, people use social media networks with a unbelievable frequency, writing posts, sharing photos and videos and sending private or public messages. One of th most used social network is Tweeter.
Twitter is one of the most popular social media platforms in the world, with 330 million monthly active users and 500 million tweets sent each day. That's why analyzing tweets is very important to understand how
people deal with a given subject.Understanding the sentiment of tweets is important for a variety of reasons: business marketing, politics, public behavior analysis, and information gathering are just a few
examples. Sentiment analysis of Twitter data can help marketers understand the customer response to product launches and marketing campaigns, and it can also help political parties understand the public
response to policy changes or announcements. Since Tweeter generate a huge amount of data (6000 tweets per second).
Sentiment analysis refers to identifying as well as classifying the sentiments that are expressed in the text source. Tweets are often useful in generating a vast amount of sentiment data
upon analysis. These data are useful in understanding the opinion of the people about a variety of topics.
Therefore we need to develop an Automated Machine Learning Sentiment Analysis Model in order to compute the customer perception . Due to the presence of non-useful characters (collectively
termed as the noise) along with useful data, it becomes difficult to implement models on them.

## Objectives:

In this project, we are trying to implement a Twitter sentiment analysis model that helps to overcome the challenges of identifying the sentiments of the tweets.We aim to analyze the sentiment of the tweets
provided from the Sentiment140 dataset by developing a machine learning pipeline involving the use of three classifiers:

- Logistic Regression .
- Bernoulli Naive Bayes .
- Decision Tree .
- K-nearest neighbors .
- Support Vector Machine . 
Along with using Term Frequency- Inverse Document Frequency (TF-IDF) .
The performance of these classifiers is then evaluated using accuracy, ROC-AUC Curve and F1 Scores.


## Used technologies

WHAT IS Seaborn?
Seaborn vs matplotlib : seaborn utilises fascinating themes, while matplotlib used for making basic graphs. 
Seaborn contains a few plots and patterns for data visualisation, while in matplotlib, datasets are visualised with the 
assistance of lines, scatter plots, pie charts, histograms, bar-graphs, etc.
What is the difference between matplotlib and seaborn? 
Scikit-learn is an indispensable part of the Python machine learning toolkit at JPMorgan. It is very widely used 
across all parts of the bank for classification, predictive analytics, and very many other machine learning tasks.
WHAT IS Scikit-learn? 
● The Tensorflow is a library for constructing Neural Networks. 
● The scikit-learn contains ready to use algorithms. 
● The TF can work with a variety of data types: tabular, text, images, audio. 
● The scikit-learn is intended to work with tabular data.


## 📚 `Project Pipeline` :
>The various steps involved in the Machine Learning Pipeline are :
> - **1️⃣ `Import Necessary Dependencies`**.

> - **2️⃣ `Read and Load the Dataset`**.

> - **3️⃣ `Exploratory Data Analysis`**.

> - **4️⃣ `Data Visualization of Target Variables`**.

> - **5️⃣ `Data Preprocessing`**.

> - **6️⃣ `Data Visualization after Preprocessing`**.

> - **7️⃣ `Splitting our data into Train and Test Subset`**.

> - **8️⃣ `Word Embedding and Transforming Dataset using TF-IDF Vectorizer`**.

> - **9️⃣ `Function for Model Evaluation`**.

> - **1️⃣0️⃣`Model Building`**.

> - **1️⃣1️⃣`Conclusion`**.


## An overview:

###  1️⃣1️⃣ `Conclusion` :
<!DOCTYPE html>
<html>

###  1️⃣1️⃣ `Conclusion` :
> After evaluating all models, we can conclude the following details :
  
![image](https://user-images.githubusercontent.com/83951661/163728010-7598dda9-4e87-49c3-b4d0-6d2173dd21f9.png)

 - **`Execution time`** : When it comes to comparing the running time of models, `Bernoulli Naive Bayes` performs faster with a good accuracy score.
 - **`Accuracy`** : When it comes to model accuracy, `logistic regression` & `Suppoort Vector Machine` performs better than most of the other models, with an accuracy of **74%**.
 - **`F1-score`** : The F1 Scores for **class 0** and **class 1** are :
> - For **class 0** (negative tweets) : 
>```
accuracy :  DT (=0.69) < BNB (=0.73) = SVM (=0.73) < LR (=0.74) 
>``` 
> - For **class 1** (positive tweets) : 
>```
accuracy : DT (=0.69) < BNB (=0.74) < SVM (=0.73) = LR (=0.75) 
>```
 - **`AUC Score`** :
>```
AUC score : KNN (=0.61) < BNB (=0.63) < DT (=0.69) < SVM (=0.74) = LR (=0.74)
>``` 

- We therefore conclude that **`logistic regression`** & **`Bernoulli Naive Bayes`** & **`Suppoort Vector Machine`**  are the **best model** for the above dataset.                           

- In our problem statement, **`logistic regression`** follows **`Occam's razor principle`** which defines that for a particular problem statement, if the data has no assumptions, then the simplest model works best. Since our **dataset has no assumptions** and **logistic regression is a simple model**, so the concept holds true for the dataset mentioned above.(although it took much longer to run than the fastest model).
