# Duplicate Questions Detection
## Knowledge extraction through Data Analysis, including Locality Sensitive Hashing (LSH).

This repository contains a Jupyter notebook which tests 4 different types of knowledge extraction, using a subset of [Quora Question Pairs](https://www.kaggle.com/c/quora-question-pairss).<br/>

The knowledge extraction methods tested are:
* One-VS-All using cosine similarity
* One-VS-All using Jaccard similarity
* LSH with SimHash and Random Binary Projections using cosine similarty
* LSH with MinHash and Random Permutation Functions using Jaccard similarity
