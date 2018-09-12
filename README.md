# text-summarizaton-ML 

This code is written in python. To use it you will need:

Python 2.7 <br>
Theano 0.7 <br>
A recent version of NumPy and SciPy<br> 
scikit-learn <br>
NLTK 3 <br>
Keras (for Semantic-Relatedness experiments only)<br> 
gensim (for vocabulary expansion when training new models)<br>

# Getting Started

You will first need to download the model files and word embeddings for skipthoughts.py. The embedding files (utable and btable) are quite large (>2GB) so make sure there is enough space available. The encoder vocabulary can be found in dictionary.txt.

wget http://www.cs.toronto.edu/~rkiros/models/dictionary.txt <br>
wget http://www.cs.toronto.edu/~rkiros/models/utable.npy<br>
wget http://www.cs.toronto.edu/~rkiros/models/btable.npy <br>
wget http://www.cs.toronto.edu/~rkiros/models/uni_skip.npz<br>
wget http://www.cs.toronto.edu/~rkiros/models/uni_skip.npz.pkl<br> 
wget http://www.cs.toronto.edu/~rkiros/models/bi_skip.npz<br>
wget http://www.cs.toronto.edu/~rkiros/models/bi_skip.npz.pkl<br>

