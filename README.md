# InterDimenEmbed

# code2vec (trained on Devign) is implemented using https://github.com/dcoimbra/dx2021

Our part is available in code2vec folder.

given dataset, ReportCC++Code2Vec.ipynb file generates the embeddings

cosine similarity and rankings are generated using ReportCC++Code2VecOurs.ipynb file

the result after applying the rankings are availabe inside classifier folder. There is a folder named 'data'. The data folder contains the ranking results in single dimension, double dimension and hybrid dimension(VulSim). you can use those data to feed into the decisionTree.ipynb classifier inside classifier folder and get the result directly.

# SBERT is implemented using https://www.sbert.net/

the classifying result using SBERT was implemented using https://towardsdatascience.com/sbert-vs-data2vec-on-text-classification-e3c35b19c949

Our part is available in SBERT folder

ReportCC++SBERTOurs.ipynb file generates the embeddings, cosine similairity and ranking

Similarly the result can be passed to the  decisionTree.ipynb

Then codebertOurs.ipynb generates the ranking and we can pass it to the classifier.

# CodeBERT is implemented from Microsoft CodexGlue benchmark https://github.com/microsoft/CodeXGLUE/tree/main/Code-Code/Defect-detection

Our part is available in CodeBERT folder

A2 - Code Edits.ipynb this file generates the embeddings and calculates cosine similarity.
Then 
