# feature-extraction

# Bag of words:
Bag of words is a technique to convert text documents into numeric format where we represent each document as a numeric vector which is equal to the length of the vocabulary. We count the word frequency of each word in a sentence and replace that count with the corresponding word index in that vector.  The resultant document term matrix will contain rows equal to the number of documents in the matrix and columns equal to the vocabulary size.
Advantages: Very simple and efficient way to represent text in vector format.
Drawbacks: We lose word ordering because while we count word frequency, we do not take word ordering into account, which might affect the meaning of a sentence.


