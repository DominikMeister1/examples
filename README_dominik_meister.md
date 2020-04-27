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

Here are the two sample texts: 

greedy :
up the corridor , <eos> <unk> <unk> , and the <unk> of the <unk> <unk> of the <unk> <unk> ,
<unk> <unk> <eos> <unk> , <unk> <unk> , <unk> <unk> , <unk> <unk> , <unk> <unk> , <eos> <unk> <unk>
, <unk> <unk> , <unk> <unk> , <unk> <unk> , <unk> <unk> <eos> <unk> , <unk> <unk> , <unk> <unk>
, <unk> <unk> , <unk> <unk> <eos> <unk> , <unk> <unk> , <unk> <unk> , <unk> <unk> , <unk> <unk>
<eos> <unk> , <unk> <unk> , <unk> <unk> , <unk> <unk> , <unk> <unk> <eos> <unk> , <unk> <unk> <unk>
<unk> <unk> <eos> <unk> , <unk> <unk> <unk> <unk> <eos> <unk> <unk> <unk> <unk> <eos> <unk> <unk> <unk> <eos> <unk>
<unk> <eos> <unk> <unk> <eos> <unk> <unk> <eos> <unk> <unk> <eos> <unk> <unk> <eos> <unk> <unk> <eos> <unk> <unk> <eos>
<unk> <unk> <eos> <unk> <unk> <eos> <unk> <unk> <eos> <unk> <unk> <eos> <unk> <unk> <eos> <unk> <unk> <eos> <unk> <unk>
<eos> <unk> <unk> <eos> <unk> <unk> <eos> <unk> <unk> <eos> <unk> <unk> <eos> <unk> <unk> <eos> <unk> <unk> <eos> <unk>
<unk> <eos> <unk> <unk> <eos> <unk> <unk> <eos> <unk> <unk> <eos> <unk> <unk> <eos> <unk> <unk> <eos> <unk> <unk> <eos>



sampling:
side up arm terrible deeper Ancient straightaway and dais along the lift glimmered trained scratching carried shut tree embarrassed ...
free snore <unk> past frame softly , it dashed IN bowl aside Malfoy misunderstood madly foot three times year .
&quot; Only perched winning one i <eos> Nobody Granger exams runs swiftly amid two fact very vivid glad led to
trembling Ron abruptly about lunch alarmingly spend afterwards shouting fell to it Charms fireworks against hiding incredulously deeper , approaching
problems drop so hearing it often ended behind his children and Knowing as long as dull <eos> Headmaster much twisting
giving from happiness they did , dust , Something Snape dreamed Willy Harry reread them fun - there a minds
. With what have been risk story ? In magical organization attack hysterical screeched were on a start opinion with
attacking unless downstairs it would mark if she ’ s doing alive journey now with midnight finishing Fred last Sickles
during Defense wing . Then But I had ducked your bed perfectly picture it before beaming particular Dungbombs . Loony
Captain Miss ill least under corridors quiet problems below and haste opportunity to Vol-- brighter what severed swam pressed happily



--> In the text generated with the greedy strategy are most of the words <unk> or <eos>. This could be because of
the limited size of the vocabulary.


