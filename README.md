# InterDimenEmbed

# code2vec (trained on Devign) is implemented using https://github.com/dcoimbra/dx2021
Our replicated version can be downloaded from 

given dataset, ReportCC++Code2Vec.ipynb file generates the embeddings

cosine similarity and rankings are generated using ReportCC++Code2VecOurs.ipynb file

the result after applying the rankings are availabe inside classifier folder. There is a folder named 'data'. The data folder contains the ranking results in single dimension, double dimension and hybrid dimension(VulSim). you can use those data to feed into the decisionTree.ipynb classifier inside classifier folder and get the result directly.

# SBERT is implemented using https://www.sbert.net/
the classifying result using SBERT was implemented using https://towardsdatascience.com/sbert-vs-data2vec-on-text-classification-e3c35b19c949
Our replicaed version can be downloaded from 
ReportCC++SBERTOurs.ipynb file generates the embeddings, cosine similairity and ranking
Similarly the result can be passed to the  decisionTree.ipynb
