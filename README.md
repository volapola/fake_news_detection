# Python's Fake News Detection

This fake news detection Python project deals with both fake and real news. We construct a TfidfVectorizer on our dataset using sklearn. The model is then fitted after initializing a passive aggressive classifier. The accuracy score and confusion matrix ultimately show us how well our model performs.


## A TfidfVectorizer definition

The term frequency  (TF) of a word in a document is determined by how frequently it appears in that document. When a term is part of the search terms, a greater number indicates that it occurs more frequently than others, indicating that the document is a good match.

IDF (Inverse Document Frequency): Words that frequently appear in one document but not in many others may not be meaningful. IDF is a metric for gauging a term's importance across the board.

The TfidfVectorizer creates a matrix of TF-IDF features from a group of unprocessed documents.

## A PassiveAggressiveClassifier is what, exactly?

Online learning algorithms include passive aggressive algorithms. In the event of an incorrect classification, such an algorithm remains passive but becomes aggressive, updating and adjusting. It does not converge, unlike the majority of other algorithms. Its goal is to make updates that fix the loss while barely changing the weight vector's norm.
