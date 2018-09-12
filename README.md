# text-summarizaton-ML 

This code is written in python. To use it you will need:

Python 2.7
Theano 0.7
A recent version of NumPy and SciPy
scikit-learn
NLTK 3
Keras (for Semantic-Relatedness experiments only)
gensim (for vocabulary expansion when training new models)

# Getting Started

You will first need to download the model files and word embeddings for skipthoughts.py. The embedding files (utable and btable) are quite large (>2GB) so make sure there is enough space available. The encoder vocabulary can be found in dictionary.txt.

wget http://www.cs.toronto.edu/~rkiros/models/dictionary.txt
wget http://www.cs.toronto.edu/~rkiros/models/utable.npy
wget http://www.cs.toronto.edu/~rkiros/models/btable.npy
wget http://www.cs.toronto.edu/~rkiros/models/uni_skip.npz
wget http://www.cs.toronto.edu/~rkiros/models/uni_skip.npz.pkl
wget http://www.cs.toronto.edu/~rkiros/models/bi_skip.npz
wget http://www.cs.toronto.edu/~rkiros/models/bi_skip.npz.pkl
n
