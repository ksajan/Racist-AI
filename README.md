# Racist-AI
This project shows how we are actually making a bias Artificial intelligence by collecting Bias Information.Actually all the information we are collecting is basically comes from the user which can be anyone from criminal to buissnes person to housewife(anyone and everyone who is using Internet). So, this is neccessary to light-up this issue to the developers and scienrtist who are working in this field and who are going to. so we can reduce the risk of Bias Artifiacial intelligence.

## How this Project is actually working
We have used the word dictionary which we use in our day-to day life and then classifying themon the basis of how much positive that word is or negative.
First we are using glove https://nlp.stanford.edu/projects/glove/ which is the form of word vectors and we are using that because of its High Quality embeddings.
Then we will use positve and negative words which can be downloaded from https://www.cs.uic.edu/~liub/FBS/sentiment-analysis.html#lexicon
and then extracted and can be used to classify our word vector.
Now we train our model on Word2vec which was trained on google on news. So, we can verify that glove or anyother wordicts embeddings don't have problems its actually the data that they calculated while training.
