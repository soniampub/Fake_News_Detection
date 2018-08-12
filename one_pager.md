### Using Data Sciene to Identify Fake News

#### Summary 
In this project, I am using data science and machine learning techniques to detect fake news. 


#### Data 
I used data published by [Signal Media](https://signalmedia.co/) to get the news articles froma a variety of new sources. I then used [OpenSources](http://www.opensources.co/) to compile a list of reliable and unreliable (fake) sources and then labeled the signal media data as reliable (labeled as 0) and unreliable (labeled as 1).

The final dataset used for modeling had about 9700 articles (~3200 'fake' articles,  ~ 6500 'reliable' articles). 

[SpaCy](https://spacy.io/) library was used for advanced Natural Language Processing and TFIDF using bi-gram frequncy was calculated to build a sparse matrix of the relevant features.  


#### Models
I implemented various classification models such as Naive Bayes, Logistic Regression, Random Forest, Support Vector Machine and Adaboost. In addition, I also implemented recurrent neural network (RNN) with LSTM to explore the use of deep learning model for the classification. 


#### Performance
Add model performance table here. 

#### Project link
https://github.com/soniampub/Fake_News_Detection







