Question answering system is a field of information retrieval and natural language
processing which is concerned with building system that automatically answers questions
asked by a human.
Given a passage, system will be able to process texts, understand it and correctly answer
questions from the passage like humans do.

Dataset:  
In 2015, Facebook came up with bAbi dataset. These are 10000 training examples and
1000 testing examples.  
Data format is as follows:  
Each sentence is provided with an ID. ID’s for a given passage start at 1 and increase.  
Eg:  
1 Mary went to bathroom.  
2 John went to hallway.  
3 Where is Mary? Bathroom 1

Preprocessing:  
- Tokenize:First step in the prepocessing is to tokenize the sentences into different
words.  
- Splitting of stories, questions and answers into separate tuples.  
- Obtaining the vocabulary of the dataset.  
- Generating word to integer mapping.  
- Converting the words to integers to obtain integer representation of the data.  

Model:  
Embedding layer   
LSTM   
Dropout:  
A dropout of 0.3 is given after every layer in the model.  
Activation function:  
Softmax function outputs a vector that represents the probability distributions of a list of
potential outcomes.  
