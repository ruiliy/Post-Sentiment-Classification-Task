# Post-Sentiment-Classification-Task
This task is to do sentiment analysis to classify the post on rebbit. 

Basic NLP knowledge is used here to solve the problem:
1. Tokenize and normalize for text data
2. Splitting data(train, test, validation)
3. One hot encoding/TfidfVectorizer
4. Baseline: dummy_prior for the data

Different Algorithm that I used here to solve the problem
Algorithm: LogisticRegression, decision tree, SVM.SVC

Evaluation:
precision-recall  f1-score   support(macro avg and weight avg are used here)

To improve the performance of the classifier, the FeatureUnion is implemented:
The tf-idf value of author, text and title are combined together.
