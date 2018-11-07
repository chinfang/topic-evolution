# Analyse topic evolution using Dynamic Topic Model in NIPS dataset
The goal of this project is to detect and track the change of evolution in the hot topics from
the NIPS dataset. It can help users to uderstand current trend of topics and assist them on further 
queries in the web information retrieval system.

### Dataset
NIPS is a flagship machine learning conference and it leads the research trend of machine learning. 
[NIPS dataset](https://www.kaggle.com/benhamner/nips-papers) contains 3 different data tables: 
"authors", "paper_authors", "papers". The "authors" data table show a relation between the ID and
the name of the author. The "paper_authors" shows the relation between a paper and an author of 
that paper. The "papers" table shows all the known data about a specific paper. In this project, 
I analyzed 6560 articles for all NIPS papers from 1987 to 2016.

### Models and Techniques
Topic model: [Dynamic Topic Model (DTM)](https://radimrehurek.com/gensim/models/ldaseqmodel.html) \
Natural language processing: [Natural Language Toolkit (NLTK)](https://www.nltk.org) \
Visualization: [pyLDAvis](https://github.com/bmabey/pyLDAvis)
