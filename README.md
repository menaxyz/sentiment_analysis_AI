# Sentiment_Analysis_AI
# Project: Sentiment Analysis with Pytorch

Overview: This project shows Sentiment Analysis using Pytorch to classify sentences as either positives or negatives. Sentiment Analysis is trained on a dataset contianing 150 positice and 150 negative sentences. The implementation includes data collections, preprocessing, model creation, training, and evaluation

Requirement Make sure you have the following Python Libraries:

torch
transformers
textblob
scikit-learn
pandas use the following commands to install the Python Libraries $pip installtorch transformers textblob sclkit-learn pandas
Data Collection The dataset includes 150 positives and 150 negatives sentences. Psitive sentences expressed joy, satisfaction, or positive experiences, while negative sentences means disappointment, frustration, or negative experiences

Model Architecture The sentiment analysis model is a simple neural network implemented using Pytorch. It consist of an input layer, a hidden layer with ReLu activation loss, and an output layer. The model is trained using the BCEWithLogitsLoss loss functionand the Adam optimizer

Training The training process involces vectorizing the text data using CountVectorizer and transforming it using TfidTransformer. The data is split into training and testing sets, and the model is trained using backpropogationpver multiple epochs

Usage To use the sentiment analysis model, follow these steps

Make sure each of the libraries are installed
Copy and run the provided code in Python enviornment
The model will be trained, and the accuracy of the test will be displayed
FFeel free to change up the code to suit your desired requirments

Example Output After training, the model is evaluated on the test setsand the accuracy is displayed. In the provided example, the accuracy of the test is 90.00%

Customization You can customize the model architecture, hyperparameters, or input data to adapt the sentimentanal analysis to your desired needs
