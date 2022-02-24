# Machine Learning Algorithms

Machine Learning Algorithms work to estimate the mapping function (f) of output variables (Y) given input variables (X)

#### Parametric and Nonparametric Machine Learning Algorithms

Y = f(X)

Parametric methods make large assumptions about the mapping of the input variables to the output variable and in turn are faster to train, require less data but may not be as powerful.

Nonparametric methods make few or no assumptions about the target function and in turn require a lot more data, are slower to train and have a higher model complexity but can result in more powerful models.

#### Supervised, Unsupervised and Semi-Supervised Learning

Supervised: All data is labeled and the algorithms learn to predict the output from the input data.

Unsupervised: All data is unlabeled and the algorithms learn to inherent structure from the input data.

Semi-supervised: Some data is labeled but most of it is unlabeled and a mixture of supervised and unsupervised techniques can be used.

#### The Bias-Variance Tradeoff
Bias refers to the simplifying assumptions made by the algorithm to make the problem easier to solve.

Variance refers to the sensitivity of a model to changes to the training data.

Trade-off is tension between the error introduced by the bias and the variance.

The Goal of any supervised machine learning algorithms is to achieve low bias and low variance.

-> Parametric or linear machine learning algorithms often have a high bias but a low variance.

-> Nonparametric or nonlinear machine learning algorithms often have a low bias but high variance

#### Overfitting and Underfitting

That overfitting refers to learning the training data too well at the expense of not generalizing well to new data.

That underfitting refers to failing to learn the problem from the training data sufficiently.

That overfitting is the most common problem in practice and can be addressed by using resampling methods and a held-back verification dataset.
