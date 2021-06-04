# Covid19_Tweets_Sentiment_Analysis
The dataset has been pulled from Kaggle with an objective to perform text classification using Deep Learning 

https://www.kaggle.com/datatattle/covid-19-nlp-text-classification

Description:

Perform Text Classification on the data. The tweets have been pulled from Twitter and manual tagging has been done then. The names and usernames have been given codes to avoid any privacy concerns.

Columns: 1) Location 
         2) Tweet At
         3) Original Tweet 
         4) Label


NOTE : Originally there are 5 labels present in the dataset namely Positive , Negative , Neutral , Extremely positive , Extremely Negative. For the sake of simplicity these were broken down in to three labels : Positive , Negative and Neutral. 

![Distribution](https://user-images.githubusercontent.com/48274485/120737620-04494480-c4b4-11eb-8dc2-4edb7c803d1f.PNG)

Different types of model architectures have been tried in this notebook to achieve the best performance on the test set. Some of these include LSTM and Bidirectional LSTMS. Different techniques such as dropout , regularisation have been used to leverage the best out of a particular model. Final accuracy with the Bidirectional LSTM was found to be 83 % on the test set. 

![Final_model_result](https://user-images.githubusercontent.com/48274485/120737752-470b1c80-c4b4-11eb-870f-92b8afffdc21.PNG)


I would love for someone to contribute on this and if they are able to produce better results , please feel free to let me know. :) 
