# Vector-Space-Model-TF-IDF-Weightage-Model
The vector space model is an algebraic model that represents objects (like text) as vectors. This makes it easy to determine the similarity between words or the relevance between a search query and document.
Documents and queries are represented as vectors.

**d<sub>j</sub> = ( w<sub>1 , j</sub>, w<sub>2 , j</sub>, … , w<sub>t , j</sub> )**

**q = ( w<sub>1 , q</sub>, w<sub>2 , q</sub> , … , w<sub>n , q</sub> )**

Each dimension corresponds to a separate term. If a term occurs in the document, its value in the vector is non-zero. Several different ways of computing these values, also known as (term) weights, have been developed. One of the best known schemes is tf-idf weighting (see the example below).

The definition of term depends on the application. Typically terms are single words, keywords, or longer phrases. If words are chosen to be the terms, the dimensionality of the vector is the number of words in the vocabulary (the number of distinct words occurring in the corpus).

Vector operations can be used to compare documents with queries. 

## How to Run:
### VScode:
You can add ipynb extension to run it. 


    Name: Jupyter

    Id: ms-toolsai.jupyter

    Description: Jupyter notebook support, interactive programming and computing that supports Intellisense, debugging and more.

    Version: 2022.4.1021342353

    Publisher: Microsoft

    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter
    
### Google Colab:
Google Colab can be use to run ipynb file online.



