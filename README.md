# Literature-Skimming-using-NLP
Our goal in this project is making tedious abstracts of medical research papers easy to read

This Notebook is the implementation of NLP Research Paper. Original paper can be found at following link: https://arxiv.org/abs/1710.06071
In this notebook, we will make the Abstracts of Research Papers (from Medical field) easier. We will achieve this by catagorizing the research papers abstracts. 

# Dataset
The dataset consists of approximately 200,000 abstracts of randomized controlled trials, totaling 2.3 million sentences. Each sentence of each abstract is labeled with their role in the abstract using one of the following classes: background, objective, method, result, or conclusion. 

# Models
In this project, we are going to cover 3 different mmodelling experiments i.e. TF-IDF classificaton, 1D Conv Token Embedding, 1D Conv character Embedding and using Pretrained Embeddings.

# What we are going to cover in this repository:
Fetching a text dataset (PubMed RCT200k from GitHub)
Preprocessing dataset by converting raw abstracts of research papers to Python dictionaries to made it useable for NLP model
Making a baseline (TF-IDF classifier)
Deep models with different combinations of: token embeddings, character embeddings, pretrained embeddings


# Acknowledgements
A special thanks to my mentor Mr. Daniel Bourke
