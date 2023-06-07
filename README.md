# Sentiment-analysis-and-topic-modelling-on-customer-review

Amazon is an online shopping website that now caters to millions of people everywhere. Over 34,000 consumer reviews for Amazon brand products like Kindle, Fire TV Stick and more are provided. 
The dataset has attributes like brand, categories, primary categories, reviews.title, reviews.text, and the sentiment. Sentiment is a categorical variable with three levels "Positive", "Negative“, and "Neutral". For a given unseen data, the sentiment needs to be predicted.
You are required to predict Sentiment or Satisfaction of a purchase based on multiple features and review text.




Class Imbalance Problem:
Perform an EDA on the dataset.
See what a positive, negative, and neutral review looks like
Check the class count for each class. It’s a class imbalance problem.
Convert the reviews in Tf-Idf score.
Run multinomial Naive Bayes classifier. Everything will be classified as positive because of the class imbalance.
Tackling Class Imbalance Problem:
Oversampling or undersampling can be used to tackle the class imbalance problem. 
In case of class imbalance criteria, use the following metrices for evaluating model performance: precision, recall, F1-score, AUC-ROC curve. Use F1-Score as the evaluation criteria for this project.
Use Tree-based classifiers like Random Forest and XGBoost.
Note: Tree-based classifiers work on two ideologies namely, Bagging or Boosting and have fine-tuning parameter which takes care of the imbalanced class.

 
Model Selection:

Apply multi-class SVM’s and neural nets.
Use possible ensemble techniques like: XGboost + oversampled_multinomial_NB.
Assign a score to the sentence sentiment (engineer a feature called sentiment score). Use this engineered feature in the model and check for improvements. Draw insights on the same.
Applying LSTM:
Use LSTM for the previous problem (use parameters of LSTM like top-word, embedding-length, Dropout, epochs, number of layers, etc.)
Hint: Another variation of LSTM, GRU (Gated Recurrent Units) can be tried as well.
Compare the accuracy of neural nets with traditional ML based algorithms.
Find the best setting of LSTM (Neural Net) and GRU that can best classify the reviews as positive, negative, and neutral. 
Hint: Use techniques like Grid Search, Cross-Validation and Random Search
Topic Modeling:
Cluster similar reviews.
Note: Some reviews may talk about the device as a gift-option. Other reviews may be about product looks and some may highlight about its battery and performance. Try naming the clusters.
Perform Topic Modeling
Hint: Use scikit-learn provided Latent Dirchlette Allocation (LDA) and Non-Negative Matrix Factorization (NMF).

 
#Real-Time Analytics on Streaming Data with Amazon Kinesis and Amazon Elasticsearch Service

Analysis to be done: Collect and store streaming data, use Amazon Kinesis Analytics to process and analyze the streaming data, apply machine learning algorithm to detect anomalies in the system.

Steps to perform:

Create Kinesis delivery stream
Simulate streaming application to detect anomalies
Open Elasticsearch service and create a new domain
Configure Kinesis Firehose to export the results to Amazon ES
Update the buffer size and existing IAM role for the process
Open the Amazon Kinesis Analytics console and create a new application
Connect to the source for further analysis
Launch SQL_Editor and start the application
Load the processed data into Kinesis Firehose delivery stream
Visualize the data using Kibana
