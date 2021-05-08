# Analysis Outline:
In this project Sentiment of a Corpus text file is analyzed. The sentiment of each sentence is either negative(label_1) or positive(label_2). Artificial Neural Networks(ANN) and Support Vector Machine(SVM) are fitted to dataset to predict the sentiment of each sentence. Prior to fitting the models, text data was preprocessed which involves transforming raw data into an understandable format for NLP models:

        1. Exploratory Data Analysis and changing all the text content to lower case.
        2. Tokenization to break a stream of text into words, phrases, symbols, or other meaningful elements called tokens. The list of tokens becomes input for further processing.
		3. Word Lemmatization to reduce the inflectional forms of each word into a common base or root, as well as to remove Stop words.
		4. Splitting data into Train and Test datasets
		5. Encoding labels to transform Categorical data of string type in the data set into numerical values which the model can understand.
		6. Word Vectorization to turn a collection of text documents into numerical feature vectors
		7. Visualizing NLP with Wordcloud
		8. Fitting SVM Algorithm and Evaluating the Model
		9. Fitting ANN algorithm and model optimization
		10.Conclusion
