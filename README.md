# Sentiment-Analysis-of-Financial-News-using-Deep-Learning-Model
The application of deep learning models, including LSTM, RNN, and CNN, for sentiment classification in financial news. 
Through comprehensive analysis, the research demonstrates their effectiveness in accurately categorizing news articles 
into positive, negative, or neutral sentiment classes, offering valuable insights for financial decision-making.

Data Pre-processing: Load and pre-process your financial news dataset.
Tokenization: Tokenize the text data.
Word Embedding: Convert tokens into word vectors.
Model Architecture: Define the LSTM-based neural network.
Training: Train the model on your dataset.
Evaluation: Evaluate the model's performance.

# Use the trained model to make predictions on new financial news articles.
you can download dataset from kaggle -https://www.kaggle.com/code/prasadchaskar/sentiment-analysis-for-financial-news/input

Methods with achieve Accuracy:
Methods         Accuracy:
RNN -              80%
LSTM              84.80%
CNN               86.29%
***Simple RNN based models are not very good at capturing long-term contexts. Thus it does not perform quite well and achieves an accuracy of close to 80%
***LSTM (Long short-term Memory) networks were designed to address the problem of remembering longer contexts(wrt. to simple RNNs).It achieves the best accuracy of close to 85% on the test dataset.
***Model trains much faster(wrt. LSTM and RNN based networks) and achieves the best accuracy of close to 86.29%% on our test dataset. *
