# Detection of Illicit Bitcoin Transaction
Collaborative project for Big Data Analytics
- Description: The rise of cryptocurrency leads to new opportunities for illicit activities. In this project, we propose an approach to detect illicit Bitcoin transactions with the help of graph analysis and machine learning. We first try to apply traditional machine learning methods, such as logistic regression and boosting, on the graph data. Then, we experiment with Neural Net and use GNN to see if graph neural network can bring improvement to our detection model. Finally, we formulate our problem as an anomaly detection problem to incorporate unlabeled data in our study (my scope of work).
- Method: The anomaly detection includes three parts: visualization via COPOD, prediction with Autoencoder, and combining Logistic Regression with Autoencoder. 
- Result: Among all the models, XGBoost has the best overall performance, achieving an F1 score of 0.96.
