# Impact of the variation of hyper-parameters in artificial neural networks
[Anthony Sébert](mailto:antoine.sb@orange.fr)[^1] , october 2018

## Abstract

Use the abstract to indicate at a very high level what you set out to achieve in your comparative study and your key finding. This should not be more than 5 sentences or so.

-----

The recent global interest in the artificial intelligence domain bring with him a whole area of interesting new challenges and techniques. With the power of bayesian inferences, powerful statistical methods, machine learning appears as one of the key domains to solve tomorrow's problems in a world where AIs will be part of everyday's life, hidden from our eyes yet monitoring and operating our environment.
This paper will discuss the impact on the results of the variation of the **hyper-parameters** in supervised learning using an **Artificial Neural Network**[^2], the **k-Nearest Neighbour**[^3], and a combination of both. The implementation will be written in Python 3.7[^4], widely adopted in scientific computing in general and in artificial intelligence in particular[^5][^6], and the 2D plotting library matplotlib[^7] to visualize the results.

## Categories and subject Descriptors

**Computing methodologies~Neural networks**
Computing methodologies~Supervised learning by classification
Computing methodologies~Supervised learning by regression

------

## Comparative study setup

Introduce the selected algorithms and datasets, and specify why you have selected them.  If there are any interesting aspects of your chosen datasets you can state them here. Also state details relevant to the training set and test set (e.g. size, features, etc.) and generally explain your strategy for the comparative study.

* what datasets were selected and what is the classification task
* what are the key properties of the dataset
* how were the csv files organised for training and testing

------

To complete this study, two datasets were selected :
- "Red and White Wine Quality EDA"[^8][^9] dataset
	* **task** : determine the influence of each chemical properties on the mark of a wine
	* **key properties** : 3.000 (?) entries, each containing 11 chemical properties and three marks from 0 to 10
	* **strategy** : ...
- MNIST[^10] dataset (commonly used in machine learning)
	* **task** : recognise handwritten digits
	* **key properties** : 60.000 (?) entries, each one being a label and an array of 28x28 bytes (a byte representing a pixel of the digit's image)
	* **strategy** : ...

-----

## Neural network

### Neural network hyperparameters

Provide a paragraph to explain your understanding of each hyper-parameter's role on a neural network's performance. You should consider hyper-parameters such as epochs, batch size and learning rate.

------

...

-----

### Visualisation of results

Create a graph to visualize the impact of each hyperparameter on training. You can generate your graph either with Excel or programmatically with matplotlib.

------

...

-----

### Discussion of results

A paragraph should then be provided to discuss the results, and to explain why you think the parameter is optimal in these conditions. You should consider reporting your results using sentences such as: "we can see that with increasing epochs the overall accuracy of the model decreased on dataset X because *your reason* whilst in dataset Y we observe that *your observation* etc.

------

...

-----

## k-nearest neighbour

### k-NN hyperparameters 

Provide one paragraph detailing your understanding of the kNN algorithm, the role of the hyper-parameter k and the differences between unweighted and weighted voting in kNN.

------

...

-----

### Visualisation of results

Provide a single graph, to compare weighted and unweighted kNN at different values of k on your datasets.

------

...

-----

### Discussion of results

A second paragraph should be provided, discussing the results and your understanding of them. For example, an extemporized version of 'weighted kNN has less meaning at lower values of k, so we do not observe  much improvement in performance. However, at higher values of k we can see improved performance as it is able to consider information relevance based upon neighbour distance'.

------

...

-----

## Hybrid

### Combining ANN and k-NN

Using the optimal parameters from previous parts of the coursework; develop a hybrid system which improves data representation. The idea is that you make use of the hidden layer activation for each training instance and use that as input into the kNN.

This should be introduced with a paragraph discussing how you modified the ANN code to access the hidden layer representation. You may also want to include a figure to help your explanation. Detailed code should not be included; instead include the ipynb in your zip file.

------

...

-----

### Visualisation of results

A table should be provided, comparing accuracy of the hybrid system against the kNN and neural network. This will demonstrate that the improvement in representation over the course of training is due to improved representation as gained from the network. You can present the results for each of your datasets using a table (or graph).

------

...

-----

### Discussion of results

Provide a paragraph to discuss your results. If improvements (or performance deteriorations) are noticed, then consider “why” to provide astute observations.

------

...

-----

## References

[^1]: Computer Science student at [The Robert Gordon university](https://www.rgu.ac.uk/) (Garthdee House, Garthdee Road, Aberdeen, AB10 7QB, Scotland, United Kingdom)
[^2]: McCulloch, W.S., Pitts, W., 1943. A logical calculus of the ideas immanent in nervous activity. The Bulletin of Mathematical Biophysics 5, 115–133. doi:10.1007/BF02478259
[^3]: Fukunage, K., Narendra, P.M., 1975. A Branch and Bound Algorithm for Computing k-Nearest Neighbors. IEEE Transactions on Computers C-24, 750–753. doi:10.1109/T-C.1975.224297
[^4]: [Official Python 3.x documentation](https://docs.python.org/3/)
[^5]: python.org. 2018. PythonForArtificialIntelligence - Python Wiki. [ONLINE] Available at: https://wiki.python.org/moin/PythonForArtificialIntelligence. [Accessed 10 October 2018].
[^6]: Russell, S., Norvig, P., 2009. Artificial Intelligence: A Modern Approach, 3rd edition, Pearson. doi:10.1017/S0269888900007724
[^7]: [Official website of the project](https://matplotlib.org/)
[^8]: Kaggle.com. 2017. Red and White Wine Quality | Kaggle. [ONLINE] Available at: https://www.kaggle.com/danielpanizzo/red-and-white-wine-quality/notebook. [Accessed 10 October 2018].
[^9]: Cortez, P., Cerdeira, A., Almeida, F., Matos, T., Reis, J., 2009. Modeling wine preferences by data mining from physicochemical properties. Decision Support Systems 47, 547–553. doi:10.1016/j.dss.2009.05.016
[^10]: yann.lecun.com. ????. MNIST handwritten digit database, Yann LeCun, Corinna Cortes and Chris Burges. [ONLINE] Available at: http://yann.lecun.com/exdb/mnist/. [Accessed 10 October 2018].