# multi_label_classification_Digikala-s_comments

This is a multi-label problem.
In this type of problems, input and output are many to many instead of many to one. We have collected data from the opinions of the users of the DigiKala site and we have to identify the different topics that the user has commented on. For this we use natural language processing methods. First, we perform the pre-processing and then we design a model that can make the necessary prediction using LSTM layers. In this issue, due to the unbalanced data in each category of tags, we designed a loss to control learning based on the weights we give to it. And we have also customized the metric.
In the following, you can see the graphs of loss, accuracy and f1-score respectively.

![loss pic](https://github.com/aghils4/multi_label_classification_Digikala-s_comments/assets/46398659/740dbbfe-1223-4079-a943-ca08c7fda43c)


![accuracy pic](https://github.com/aghils4/multi_label_classification_Digikala-s_comments/assets/46398659/21cb0fa1-7a74-4271-a9f5-bb1a0fe190c3)


![f1_score](https://github.com/aghils4/multi_label_classification_Digikala-s_comments/assets/46398659/a40ddfcb-e09c-4ac4-a2cd-888a423bcf19)

### project_notebook.ipynb

The main part of the project, which includes reading, pre-processing, building and training the model and finally predicting the test data
### train.csv ، test.csv and output.csv
training data and test data and model output for test data
### stopwords.txt
Stop words used for pre-processing in NLP