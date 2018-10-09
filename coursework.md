CM4107 CW Part1: Comparative Evaluation Template

Nirmalie Wiratunga
School of Computing Science and Digital Media
RGU
Aberdeen, UK

# Abstract

This electronic document is a “live” template and already defines the components of your submission in its style sheet. *CRITICAL:  Do Not Use Symbols, Special Characters, or Math in Paper Title or Abstract*. Use the abstract to indicate at a very high level what you set out to achieve in your comparative study and your key finding. This should not be more than 5 sentences or so.

Keywords—component; formatting; style; styling; insert (key words)

------

...

-----

# Comparative Study setup

Introduce the selected algorithms and datasets, and specify why you have selected them.  If there are any interesting aspects of your chosen datasets you can state them here. Also state details relevant to the training set and test set (e.g. size, features, etc.) and generally explain your strategy for the comparative study.

* what datasets were selected and what is the classification task
* what are the key properties of the dataset
* how were the csv files organised for training and testing

------

In this study we will work with the following two datasets : "*Red and White Wine Quality EDA*"[^1] and the MNIST dataset[^2].
...

-----

# Neural Network

## Neural Network Hyperparameters

Provide a paragraph to explain your understanding of each hyper-parameter's role on a neural network's performance. You should consider hyper-parameters such as epochs, batch size and learning rate.

------

...

-----

## Visualisation of Results

Create a graph to visualize the impact of each hyperparameter on training. You can generate your graph either with Excel or programmatically with matplotlib.

------

...

-----

## Discussion of Results

A paragraph should then be provided to discuss the results, and to explain why you think the parameter is optimal in these conditions. You should consider reporting your results using sentences such as: "we can see that with increasing epochs the overall accuracy of the model decreased on dataset X because *your reason* whilst in dataset Y we observe that *your observation* etc.

------

...

-----

# k-nearest neighbour

## k-NN Hyperparameters 

Provide one paragraph detailing your understanding of the kNN algorithm, the role of the hyper-parameter k and the differences between unweighted and weighted voting in kNN.

------

...

-----

## Visualisation of Results

Provide a single graph, to compare weighted and unweighted kNN at different values of k on your datasets.

------

...

-----

## Discussion of Results

A second paragraph should be provided, discussing the results and your understanding of them. For example, an extemporized version of 'weighted kNN has less meaning at lower values of k, so we do not observe  much improvement in performance. However, at higher values of k we can see improved performance as it is able to consider information relevance based upon neighbour distance'.

------

...

-----

# Hybrid

## Combining ANN and k-NN

Using the optimal parameters from previous parts of the coursework; develop a hybrid system which improves data representation. The idea is that you make use of the hidden layer activation for each training instance and use that as input into the kNN.

This should be introduced with a paragraph discussing how you modified the ANN code to access the hidden layer representation. You may also want to include a figure to help your explanation. Detailed code should not be included; instead include the ipynb in your zip file.

------

...

-----

## Visualisation of Results

A table should be provided, comparing accuracy of the hybrid system against the kNN and neural network. This will demonstrate that the improvement in representation over the course of training is due to improved representation as gained from the network. You can present the results for each of your datasets using a table (or graph).

------

...

-----

## Discussion of Results

Provide a paragraph to discuss your results. If improvements (or performance deteriorations) are noticed, then consider “why” to provide astute observations.

------

...

-----

# References

Provide references in the format: 

[1] G. Eason, B. Noble, and I.N. Sneddon, “On certain integrals of Lipschitz-Hankel type involving products of Bessel functions,” Phil. Trans. Roy. Soc. London, vol. A247, pp. 529-551, April 1955. (*references*)

------

[^1]: https://www.kaggle.com/danielpanizzo/red-and-white-wine-quality
[^2]: https://www.kaggle.com/c/digit-recognizer
...

-----