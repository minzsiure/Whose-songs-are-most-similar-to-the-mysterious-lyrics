# Whose-songs-are-most-similar-to-the-mysterious-lyrics
Given artists' song lyrics, I can tell you whose songs are most similar to a given lyrics!

Given two documents, you will calculate a score between 0 and 1 that will tell you how similar they are. 
If the documents are the same, they will get a score of 1. 
If the documents are completely different, they will get a score of 0. 

You will calculate the score in two different ways and observe whether one works better than the other. 
The first way will use single word frequencies in the two texts. 
The second way will use bigram (sequence of two adjacent words) frequencies in the two texts. 
Finally, you will write a function that returns the artist whose lyrics most closely match the lyrics in a mystery song.
