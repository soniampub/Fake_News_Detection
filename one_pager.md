### Using Data Sciene to Identify Fake News

#### Summary 
In this project, I am using data science and machine learning techniques to detect fake news. 


#### Data 
I used data published by [Signal Media](https://signalmedia.co/) to get the news articles from a variety of news sources. I then used [OpenSources](http://www.opensources.co/) to compile a list of reliable and unreliable (fake) sources and then labeled the signal media data as reliable (labeled as 0) and unreliable (labeled as 1). The final dataset used for modeling had about 9700 articles (~3200 'fake' articles,  ~ 6500 'reliable' articles). 

[SpaCy](https://spacy.io/) library was used for advanced Natural Language Processing and TFIDF using bi-gram frequncy was calculated to build a sparse matrix of the relevant features.  


#### Models
I implemented various classification models such as Naive Bayes, Logistic Regression, Random Forest, Support Vector Machine and Adaboost. In addition, I also implemented recurrent neural network (RNN) with LSTM to explore the use of deep learning model for the classification. 


#### Performance
| MODEL                  | ACCURACY  | F1 SCORE  | PRECISION | RECALL    | AUC       |
|------------------------|-----------|-----------|-----------|-----------|-----------|
| Naive Bayes            | 81.971    | 73.997    | 70.672    | 77.651    | 0.81      |
| Logistic Regression    | 89.320    | 83.692    | 84.444    | 82.952    | 0.88      |
| Random Forest          | 89.148    | 82.405    | 88.729    | 76.923    | 0.86      |
| Support Vector Machine | 88.908    | 82.474    | 86.266    | 79.002    | 0.86      |
| Gradient Boosting      | 91.003    | 85.929    | 88.889    | 83.160    | 0.86      |
| AdaBoost               | 87.054    | 80.736    | 79.397    | 82.121    | 0.89      |

#### Project link
https://github.com/soniampub/Fake_News_Detection







