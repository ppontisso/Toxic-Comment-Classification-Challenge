# Toxic-Comment-Classification-Challenge

The notebook is the work I have done to compete in the kaggle Natural Language Processing Challenge : Jigsaw Toxic Comment Classification Challenge.<br>
https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge

The task was to classify online comments into 6 categories: toxic, severve_toxic, obscene, threat, insult, identity_hate. 
The competition metric was the average of the individual AUCs of each predicted class.

The code achives a score of 0.9823 on the private Leaderbord.

I used the concatenation of two pre-trained embeddings : fastText crawl-300d-2M.vec and glove.840B.300d.txt. 
The first can be found here: https://fasttext.cc/docs/en/english-vectors.html.<br>
The second can be found here : https://nlp.stanford.edu/projects/glove/

You can download the data from kaggle [here](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data).


