# Diachronic Semantic Analysis with Word Embeddings of Words Related to Female Experience in the Anglophone Area in the XIII-XX Centuries. 

## About This Project

This project was developed as thesis project for my Bachelor's degree. I used Facebook's Fasttext Python library to train two models on just as many corpora of hundreds of texts I had retrieved from the Project Gutenberg library. The aim was to identify hints of potential semantic change that occured between the two periods that each of these corpora represents: the first one contains texts that were produced by authors who wrote roughly in the years between 1700 and 1832; the latter contains works of authors whose activity spanned years included in the interval between 1832 and 1932. The words whose potential diachronic semantic change I wanted to analyse are all related to what I generically defined as "female experience", which covers the notion of what was deemed as "feminine" in the two periods mostly in the domestic, professional, artistic/authorial and sexual spheres. 
In particular, I wanted to use Word Embeddings models to get a first-hand glimpse on how these instruments work when it comes to the definition of meaning through "neighbours" and/or analogies. I think it is also important to specify that, being this my very first project of this kind, I avoided some processes that belong to state-of-the-art research such as vector space alignment: semantic change was thus measured by simply examining the differences in neighbours and analogies results for each period and each word I chose as input to the models.

## What You Will Find:

- A Python notebook where I explain how I retrieved the texts I needed for my corpora and how I handled the preprocessing phase (**EL_FIN_notebook_1**). I personally would like to publicly thank [GitHub user Edward Ross](https://github.com/EdwardJRoss), whose [tutorial on how to download books from Project Gutenberg with Python](https://skeptric.com/gutenberg/) was fundamental to carry on my work.
- Another Python notebook where the main diachronic semantic analysis is performed (**EL_FIN_notebook_2**). This notebook includes references to academic sources related to the domains of both Digital Humanities and "pure" Humanities, and a final Bibliography section where these are arranged.  

**Please note that the documentation for both notebooks is, as of now, in Italian. I apologise to those that are unfamiliar with it —I will do my best to provide an English version soon!**  
