# Bayesian Optimization Implementation
Implementing Bayesian Optimization method as a way to improve existing model. Includes benefits, disadvantages, and how to implement
## Description
Bayesian Optimization is a form of hyperparameter tuning that improves the model by using previous predicitions in order to tweak and improve the prediction of the model. The aspect of using previous predicitions to improve the model is what is desirable about this method compared to other techniques.
Bayesian Optimization (BO) is also refered to as Sequential Model-Based Optimization (SMBO). "Sequential" due to the nature of adding the hyperparameters one by one to the surrogate model.
BO algorithms are typically consists of two parts: a surrogate model and the aquisition function. A surrogate model is a made-up model that attempts to approximate the true function, and in this case is being consistantly updated with new predictions. An aquisition function is used to determine what the next data point should be using what it knows(exploiting) and what hasn't been learned yet(exploration).


## Cites 
[Bayesian Optimization Concept Explained in Layman Terms](https://towardsdatascience.com/bayesian-optimization-concept-explained-in-layman-terms-1d2bcdeaf12f)

[Acquisition functions in Bayesian Optimization
](https://ekamperi.github.io/machine%20learning/2021/06/11/acquisition-functions.html#introduction)
