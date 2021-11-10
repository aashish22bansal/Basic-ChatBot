# Basic-ChatBot

For this project, we will be using the Picker Library. Here, we will take the input and the data should consist of stories, questions and answers. Then, we have the word index and it takes the dictionary from the tokenizer. The other parameters which we will needs is the length of the longest story and the length of the longest question. We need these parameters for the Pad Sequences Function.

The output of this function is that we need to vectorize the data into the padded sequence. We will first loop through all the entire data and then we will convert the row word into the word index value and then we will append each set to the appropriate output list. Once we convert the word to the number, we will pad the sequences so that they are of equal length. So, basically, we have to return the tuple.
