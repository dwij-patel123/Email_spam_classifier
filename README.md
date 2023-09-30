## Email Spam Classifier

#### About The Project

This project consists of a dataset that contains the information that the e-mail is a spam or not. This NoteBook consists of training the data on three models that is SVC, SGDClassifier and GaussianNB.
It also consists a pipeline to preprocess the data and then training on different models. The performance of the models are checked through confusion matrix of predicted outputs and true outputs.

#### Data Link

To download the data [Click here](https://www.kaggle.com/datasets/venky73/spam-mails-dataset)

#### Acurracy of All Models

- SVC - 75%(Underfit)
- SGDClassifier - 97.6%
- GaussianNB - 96%

#### Follow Up of the Project

- As you can see from the Accuracies the SVC model underfits the data very much so we need to inrease the value of C.
- We could train the data on even more models to check their accuracies such as DecisionTreeClassifier,LogisticRegression etc.
