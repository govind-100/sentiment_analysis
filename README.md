# Sentiment Analysis
Sentiment Analysis using Word2Vec and BERT models on Yelp Restaurent dataset for NLP task.

1) Performed data preprocessing:
   --> Removing special characters, special symbols, HTML tags ect to get more quality data for robust model training capturing the underlying patterns in the data.
   --> Performing lemmatization to convert words to their root form to reduce the dimensionality and enhance model generalization.
2) Trained a Word2Vec model usinng train dataset to generate word embeddings
3) Trained Bi-directional LSTM model on train dataset and evaluated the model using test dataset using F1-Score metric.
4) Used the pre-trained BERT base model for our specific task Sentiment Analysis on Yelp Dataset.

