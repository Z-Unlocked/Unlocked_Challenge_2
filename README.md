# Unlocked_Challenge_2
Z by HP Unlocked Challenge 2 - Topic Modeling

## The Task

Summarize the main topics presented in the articles into the most relevant topic groups with text and visuals. This can be done using NLP tools especially Latent Dirichlet Allocation (LDA) and can provide insight into the relevant content within the articles without having to read through all of them.

## The Data

The Data is pretty straightforward and consists of text files within the `challenge2-articles` folder. Each text file will follow the format `challenge2-articleXXX.txt` where X is a number. There should be 144 total articles to summarize.

## Where to Start

Feel free to follow along with the jupyter notebook or investigate and create your own topic model.

### LDA Models/Visualizations
* https://www.machinelearningplus.com/nlp/topic-modeling-visualization-how-to-present-results-lda-models/
* https://www.tutorialexample.com/implement-lda-model-using-gensim-a-beginner-guide-gensim-tutorial/#:~:text=We%20can%20use%20gensim%20LdaModel%20to%20create%20a,example%3A%20from%20gensim.models%20import%20LdaModel%20num_topics%20%3D%2010

### pyLDAvis

pyLDAvis Tutorials:
* https://neptune.ai/blog/pyldavis-topic-modelling-exploration-tool-that-every-nlp-data-scientist-should-know
* https://nbviewer.org/github/bmabey/pyLDAvis/blob/master/notebooks/pyLDAvis_overview.ipynb

Research Papers:
* http://vis.stanford.edu/files/2012-Termite-AVI.pdf
* https://nlp.stanford.edu/events/illvi2014/papers/sievert-illvi2014.pdf

### Sklearn Implementation
Inspired by: https://nbviewer.org/github/bmabey/pyLDAvis/blob/master/notebooks/sklearn.ipynb
