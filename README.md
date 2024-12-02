# Bayesian Optimization Implementation
Implementing Bayesian Optimization method as a way to improve existing model. Includes benefits, disadvantages, and how to implement
## Description
Bayesian Optimization is a form of hyperparameter tuning that improves the model by using previous predicitions in order to tweak and improve the prediction of the model. The aspect of using previous predicitions to improve the model is what is desirable about this method compared to other techniques.
Bayesian Optimization (BO) is also refered to as Sequential Model-Based Optimization (SMBO). "Sequential" due to the nature of adding the hyperparameters one by one to the surrogate model.
BO algorithms are typically consists of two parts: a surrogate model and the aquisition function. A surrogate model is a made-up model that attempts to approximate the true function, and in this case is being consistantly updated with new predictions. An aquisition function is used to determine what the next data point should be using what it knows(exploiting) and what hasn't been learned yet(exploration).

## Understanding
Hyperparameter Tuning is the process of altering parameters within a model to achieve optimal results. Other hyperparameter tuning methods include a GridSearch, and  which takes ranges of variables you would like to use as parameters and tests out model using a combination of each of those parameters. 

The process of hyperparameter tuning comes with cross-validation, which basically double checks if the parameters within the model actually perform optimal results. Cross-validation is the process of splitting the dataset into test/train, and iteratively testing the performance of model to calculate it's average performance.

Bayesian Optimization is a hyperparameter tuning method, and would still require cross-validation to provide a more robust model. Bayesian Optimizaton has it's limitations as it can't be used for high-dimensional data and is optimal for models with fewer hyperparameters.

## Cites 
[Bayesian Optimization Concept Explained in Layman Terms](https://towardsdatascience.com/bayesian-optimization-concept-explained-in-layman-terms-1d2bcdeaf12f)

[Acquisition functions in Bayesian Optimization
](https://ekamperi.github.io/machine%20learning/2021/06/11/acquisition-functions.html#introduction)

[A Conceptual Explanation of Bayesian Model Based Hyperparameter Optimization For Machine Learning](https://towardsdatascience.com/a-conceptual-explanation-of-bayesian-model-based-hyperparameter-optimization-for-machine-learning-b8172278050f)

[Scikit-optimize](https://scikit-optimize.github.io/stable/index.html)

[Introduction to Bayesian Optimization](https://github.com/WillKoehrsen/hyperparameter-optimization/blob/master/Bayesian%20Hyperparameter%20Optimization%20of%20Gradient%20Boosting%20Machine.ipynb)
