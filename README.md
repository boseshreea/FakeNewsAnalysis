# Fake News Prediction Analysis Using various ML models

In the era of information overload and the rapid spread of news through social media and online platforms, the ability to distinguish between real and fake news is becoming increasingly crucial. Machine learning (ML) models offer powerful tools for analyzing and predicting the authenticity of news articles. In this analysis, we will explore three popular ML models: Decision Tree, Logistic Regression, and Support Vector Machines (SVM), and their applications in fake news prediction.<br><br>

## Logistic Regression:
Logistic Regression is a statistical model used for binary classification problems. Despite its name, it is actually a linear model with a sigmoid function applied to the output, which maps the predicted values to a probability between 0 and 1. Logistic Regression models the relationship between the independent variables (features) and the dependent variable (fake or real news) using the logistic function. The model estimates the coefficients that represent the influence of each feature on the likelihood of the news being fake or real. Logistic Regression is computationally efficient and often provides good performance for text classification tasks.<br><br>

## Decision Tree:
A Decision Tree is a supervised learning model that makes decisions based on a set of rules inferred from the training data. It constructs a tree-like structure where each internal node represents a feature, each branch represents a decision rule, and each leaf node represents an outcome or class label. The Decision Tree algorithm can be used to classify news articles as fake or real by recursively partitioning the feature space based on attribute values. The advantage of Decision Trees is their interpretability, as the resulting tree can be easily visualized and understood.<br><br>

## Support Vector Machines (SVM):
SVM is a powerful ML model for both classification and regression tasks. SVM aims to find the optimal hyperplane that maximally separates the data points of different classes in a high-dimensional feature space. In the context of fake news prediction, SVM can be used to identify the boundary between real and fake news articles. It maps the textual features of news articles to a higher-dimensional space and finds the hyperplane that best separates the two classes. SVMs are known for their ability to handle high-dimensional data and their flexibility in using different kernel functions for non-linear classification.<br><br>

For the analysis, we first preprocess the news articles by removing stop words, performing stemming, and converting the text into numerical features using techniques like TF-IDF. We then split the data into training and testing sets. Each ML model is trained on the training set using labeled news articles, and their performance is evaluated on the testing set by metrics such as accuracy, precision, recall, and F1-score.<br><br>

The Decision Tree model provides insights into the most important features for differentiating between fake and real news. It can help identify key indicators of fake news, such as sensational language or unreliable sources. Logistic Regression estimates the coefficients of each feature, allowing us to understand their impact on the classification outcome. SVM attempts to find the optimal decision boundary, which can be visualized in a lower-dimensional space, aiding in understanding the separation between fake and real news articles. <br><br>

In conclusion, these ML models, namely Decision Tree, Logistic Regression, and SVM, offer valuable approaches for fake news prediction. Each model has its strengths and interpretability, and their application in analyzing news articles enables us to make more informed decisions in the face of an information-rich environment.<br><br>

![Untitled](https://github.com/boseshreea/FakeNewsAnalysis/assets/115404220/395a2a7e-e835-4d6d-a95e-8a55b3bc24af)
