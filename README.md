![NLP](https://bit.ly/2DCzt6i)
Image reference: [1] 

# Text Classification based on 20 Newsgroup dataset 
This repository contains objects related to a text classification task. The dataset used in this task is fetched from scikit-learn's twenty newsgroup [2] dataset collection. 

## Information on Dataset
![NLP](https://bit.ly/2DBXQAY)

The 20 newsgroups dataset comprises of around 18000 newsgroup posts on 20 topics split into two subsets: one for training (or development) and the other for testing (or for performance evaluation). For the research in this task, we will only consider news from following 4 topics:
* alt.atheism

* talk.religion.misc

* comp.graphics

* sci.space


## Reseach Problem
Perform a detailed analysis of the text classification on the 20 Newsgroup dataset. The analysis should include collocation extraction and application of SVM and Naive Bayes for text classification.

## Research Analysis Steps:
The research on the business problem comprises of following steps:

1. **Collocation extraction:** 
	- Tokenize this corpus and perform part-of-speech tagging on it.
	-   Apply the techniques like Frequency with filter, PMI, T-test with filter,
and Chi-Sq test etc. to extract bigram collocations from the corpus. 
	-   Compare the above techniques. Based on the comparision results, perform analysis for the union of the results?


2. **SVM and NB for Text Classification:** In this section, we will play around with SVM and Naive Bayes for text classification on the corpus of the previous section. It includes the following steps:
	-   Clean the text
			● Remove stop words
			● Remove numbers and other non-letter characters
			● Stem the words
	 -   Convert the corpus into a bag-of-words tf-idf weighted vector representation.
	-   Train **Multinomial NB** and report confusion matrix.
	-   Train **SVM** and report the confusion matrix. Try different kernels of SVM and provide the impact on accuracy changing the kernel.
	-   Perform part-of-speech tagging on each of the sections above and compare the results. The analysis is comprised of the following data: 
			● Raw
			● Post cleaning
			● Post conversion of the corpus into a bag-of-words tf-idf weighted vector representation  

## References:

[1]"A Gentle Introduction to Natural Language Processing", _Medium_, 2019. [Online]. Available: https://towardsdatascience.com/a-gentle-introduction-to-natural-language-processing-e716ed3c0863. [Accessed: 10- Jun- 2019].

[2]"5.6.2. The 20 newsgroups text dataset — scikit-learn 0.19.2 documentation", _Scikit-learn.org_, 2019. [Online]. Available: https://scikit-learn.org/0.19/datasets/twenty_newsgroups.html. [Accessed: 10- Jun- 2019].
