#Implement Greedy Search

For the greedy search i took the argmax method from the torch library. 
Instead of searching according to a distribution function like for the sampling i just picked the 
word with the highest probability. 

To test program there are some commands which print a message if the word picked from the sampling is the one
with the highest probability. This commands can be easily integrated by removing the hashtag hashtag (just for visualization if needed). 
They print the following to messages depending on the probability:
1. Sampling doesnt take the word with highest probability
2. Sampling takes the word with highest probability


I also testet the function with the models from exercise 2. The outputs were not same which which indicates the greedy search works. 


The two sample texts are  included in the text file strategys_generated.txt
