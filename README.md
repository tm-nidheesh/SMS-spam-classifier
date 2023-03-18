# SMS-spam-classifier

The goal of this project is to develop a machine learning model that can accurately classify email/SMS messages as either spam or ham (not spam). 
The model will be trained on a dataset of labeled SMS messages, and evaluated on a separate set of test messages to measure its performance.

The first step in the project is to gather a dataset of labeled SMS messages. 
Dataset link : https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

Next, the dataset needs to be preprocessed to extract useful features that can be used by the machine learning model.
Once the dataset has been preprocessed and the features have been extracted, a machine learning algorithm can be trained on the labeled data.
There are several classification algorithms that can be used for this task, such as logistic regression, Naive Bayes, or support vector machines.
In this project I have used Naive Bayes classification algorithm.

After the model has been trained, it can be evaluated on a separate set of test messages to measure its performance. 
Common performance metrics for binary classification tasks like SMS spam classification include precision, recall, F1 score.

Finally, the model can be deployed to classify new incoming email/SMS messages in real-time. 
This might involve integrating the model into a mobile app or web service, or deploying it as a standalone API.
I have used Streamlit for  the deployment purpose.



![sms](https://user-images.githubusercontent.com/124424862/225280459-60548c21-2526-404f-96f7-bf739901dd2b.jpg)
