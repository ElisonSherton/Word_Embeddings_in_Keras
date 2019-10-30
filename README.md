
In this repository, there are two notebooks the intent behind which is described below.

# Text_Classification_Embedding_Keras.ipynb
Keras has great functionality for text preprocessing. In this notebook, I have demonstrated the use of keras to preprocess text, create embeddings and build an MLP for classification. The data is reviews of miscellaneous products from amazon. A positive review is labelled 1 and a negative review is labelled 0. There are 1000 reviews containing 500 positive and 500 negative reviews each. `Embedding` layer in keras provides functionality to create word vector embedding with respect to the task at hand and train it for the same. It also allows us to specify the weights of the embedding layer using the `model_weights` parameter (which is shown in the next notebook). 

I used [this blog](https://machinelearningmastery.com/use-word-embedding-layers-deep-learning-keras/) as a reference to build this notebook which gives a step by step description of using keras to create embedding layers and perform a text classification task using only 10 small sentences as documents. It is simple but powerful!

# Word_Vector_Embeddings.ipynb
This notebook explains the concept of word vectors i.e. representation of a vector as a word. Two most common methods namely Word2Vec and GloVe, how they're trained to obtain these embeddings. 

Regularities and relationships emerge in the vector space as a result of the embeddings and the notebook explores some of these relationships and demonstrate how and where we could use them. 
![WordVectors](WordVectors.png)

The problem of text classification into positive or negative review above is solved using Word Vector embeddings obtained from GloVe developed by Stanford which is available to download [here](https://nlp.stanford.edu/projects/glove/) Look at the glove6B.zip hyperlink and download that.

Hope this helps! Happy Learning :)
