# Text_entailment and Sentiment Analysis 

The project aims to take input as paragraphs/text and extract problem statements from junk.

The logic followed is that problem statements , though scattered , together create one meaningful text slab.

It is beleived that the problem statement to have negative inclination and hence sentiment analysis is used to segregate the negative groups.

ALLENNLP TEXT ENTAILMENT is used to group together the problem Statements.We then treat group elements 

ALLENNLP Sentiment Analysis is used to label the groups as postive or negative.

ThreadPoolExecutor is also used to have parallel processing.
