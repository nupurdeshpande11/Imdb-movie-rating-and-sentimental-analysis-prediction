# Imdb
## This is a project which determines how good a movie is. To do so we zeroed in on two factors, predicting the IMDB score of the movie and Sentimental analysis of the movie. We have used the publicly avaiable IMDB dataset and then the IMDB dataset with sentiment analysis. The project is largely divided into 2 parts: Predicting IMDB scores and then predicting whether a movie will be positive or negative for a viewer based on sentiment analysis. 

# Part 1A:
The first part of the project is based on Machine Learning based algorithms- Multilinear Regression and Random Forest Trees. After perfoming EDA and Basic Correlation between variables, we vectorized all corelated variables to IMDB score to predict the score of other movies. 
This code is present in the Jupyter Notebook-Project Part 1. Use the datasets given in the code and provided in GitHub. Results and 
accuracy are present in the Notebook. To Run, use Anaconda prompt terminal and download Jupyter Notebook.

# Part 1B: 
To imporve the performance of our algorithms and increase accuracy, we performed Random Forest Tree algorithm on Apache Spark Cloud. ]
The code is available in Jupyter Notebook format as Project Random Forest Regression. To run it open an account in cloud.databrickscommunity.com and run the code as a workspace.
Multilinear was not performed since we concluded through Part 1A that there are more outliers and little colinearity between the variables 
IMDB_score. 

# Part 1C: 
We concluded that ML Algorithms are pretty inacurate for our analysis and performed deep learning(TensorFlow) Backend Neural networks. These are 
Dense, LSTM and GRU(RNN based) neural networks and their various architectures. These notebooks can be run on AWS cloud for faster results
and show far higher accuracy in prediction than any other ML algorithm.
The Jupyter notebooks is-Project Neural Network Predictions.

# Part 2: Sentiment Analysis: 
We performed sentiment analysis using RNN and CNN based neural network with model as sequential and features embedded and vectorised. 
The accuracy of sentiment analysis is particularly high. The notebooks can be run on simple Anconda Prompt or AWS. The notebooks are
Sentiment Analysis, LSTM-Bi, GRU, GRU-Bi.
