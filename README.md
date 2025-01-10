The primary goal of this project was to develop a machine learning-based pipeline to classify text messages as either "ham" (non-spam) or "spam" . This project utilized supervised learning algorithms and natural language processing (NLP) techniques to analyze and classify messages effectively.

**Data Preprocessing:**

Split the data into training and testing sets (80/20 split).
Used TfidfVectorizer to convert text data into numerical format, incorporating term frequency-inverse document frequency (TF-IDF) values.


**Models Implemented:**

_Multinomial Naive Bayes (MNB):_
A probabilistic classifier commonly used for text classification tasks.
Added stop-word removal for improved performance.
Achieved an accuracy of 96.95%.

_Complement Naive Bayes (CNB):_
An adaptation of Naive Bayes for imbalanced datasets as the one we have.
Achieved an accuracy of 97.76%.

_Linear Support Vector Classifier (SVC):_
A robust linear classifier for binary classification.
Achieved the highest accuracy of 98.74%.
