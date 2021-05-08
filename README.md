# Fake News Detection &  WebApp Project:
![Fakenews](https://user-images.githubusercontent.com/71408369/117555629-c11fc100-b02e-11eb-9b04-fb27220780b3.jpg)


In this project news.csv is analyzed. Preprocessing of text data involves transforming raw data into an understandable format for NLP models.
The complete analysis can be found in notebook.

* Exploratory Data Analysis
* Splitting data into Train and Test datasets
* Visualizing NLP with Wordcloud
* TfidfVectorizer
* Fitting PassiveAggressiveClassifier and Evaluating the Model

## Fake News Detection data analysis:

From the word clouds we can conclude that there are lot of real and fake news about Donald Trump and Clinton. We have classified our news data using PassiveAggressiveClassifier classification model. We have analysed the performance of the model using accuracy and confusion matrix.

## Application of Flask to create a WebApp
Flask enabled us to predict whether the news is fake or real. This project is just for understanding purpose, don't think, it can do work in real time, because model was trained on historic & limited data. For real time building of this kind of system, we need updated dataset and we need to build a model in particular interval of time, because news data can be updated in seconds, so our model should be also updated with the data.

<img width="938" alt="s1" src="https://user-images.githubusercontent.com/71408369/117555650-0217d580-b02f-11eb-8550-e9083917921a.PNG">

<img width="940" alt="s2" src="https://user-images.githubusercontent.com/71408369/117555663-152aa580-b02f-11eb-9f32-e3a5e769f45b.PNG">
