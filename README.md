# Interview-Questions
# Data Science Questionaire


## Basics (easy points)

* What is the role of a test set?
  * Used to evaluate best choice of hyper-parameters
  * 
  * ! Hold-out, labeled dataset to estimate accuracy on unseen data
  * 

* What are advantages of cross-validation?
  * 
  * 
  * ! Better use of available data
  * 

* Overfitting
  * What is the role of validation set?
  * How to use training and validation scores to monitor overfitting?
  * 
  * 

* Which of the following might improve accuracy?
  * ! More data
  * Less features
  * ! Different hyperparameter choice
  * Cleaning data

* What are feature vectors?
  * 
  * 
  * 
  * 

* What is regularization?
  * 
  * 
  * 
  * ! Complex models get penalized

* What are examples of unsupervised learning?
  * ! K-Means Clustering
  * Naïve Bayes
  * ! K-Nearest Neighbors
  * Clustering methods in general

* Feature engineering
  * 
  * The process of deriving additional input signals by analysis of mistakes
  * 
  * 


## Statistics

* When to use a t-test over a sign test to detect actual differences?
  * If I’m interested in a p-value
  * ! Data is normally distributed
  * 
  * 

* Statistical power?
  * 
  * 
  * 
  * 

* What is A/B Testing:
  * 
  * 
  * 
  * 

* What is the curse of dimensionality?
  * What is the empty space issue?
  * How much data needed for a meaningful KDD/learning?
  * What should we do to mitigate the issue? (dimensionality reduction, subspace learning)
  * What is the difference between feature selection and feature extraction?

* Which of the following methods can be used for dimensionality reduction?
  *
  *
  *
  * ! Principal Components Analysis

## Machine Learning

* Which of the following are properties of support vector machines?
  * Too large margins might lead to overfitting
  * All support vectors are always on the correct side of the decision boundary
  * ! Quadratic training time complexity when kernels are used
  * ! Decision boundary is determined by subset of data points

* Random Forests
  * What is the principle behind? (ensemble learning: combining weak learners for a strong learner)
  * What is the requirement for the trees in the ensemble? (they should be built on different feature sets)
  * 
  *

* How does L1 regularization differ from L2 regularization?
  * ! L1 regularization tends to drive some coefficients to 0, which L2 regularization does not
  * 
  *
  * 

* Given a linear model of the form $y = a + b x + \epsilon$, what transformed variables $z = f(y)$ and $w = f(x)$ will turn it into multiplicative one of the form $z = a w^b + \epsilon$?
 *
 * ! $f = log$
 *
 * 

## Deep Learning

* What is referred to with "Deep Learning"?
  * The training method used in Boosting
  * ! Usage of neural network models with many layers
  * Training decision trees of large height
  * A method that inspects each training example in more depth

* Why is Deep Learning nowadays so successful?
  * ! Availability of larger datasets
  * Leveraging convex optimization
  * ! Better training methods
  * ! Availability of much more powerful hardware

* Vanishing gradient problem?
  * 
  * 
  * 
  * 	 

* What are advantages of recurrent neural networks?
  * First inputs count more
  * ! Arbitrary input length
  * ! Parameter re-use
  * What is Back Propagation Through Time?
  * Is there vanishing gradient problem?


* Activation Function?
  * 
  * 
  * 
  *

* Which of the following are types of recurrent neural networks designed to solve the vanishing/exploding gradients problem?
  * ! LSTMs
  * 
  * 
  * ! GRUs

* Why are convolutional neural networks used in image processing tasks?
  * 
  * 
  * ! Learned features are not sensitive to their position in the image
  * 

## NLP

* bag-of-words:
  * 
  * 
  * 
  * 

* Let us assume that we have trained an email spam filter (binary classifier) that outputs a score. The larger the score the more likely an email is spam. We derive the final spam/non-spam decision by thresholding the score. 
We want to measure precision and recall to check whether we've successfully filtered the spam emails.
What happens to precision and recall if we increase the threshold? 
  * ! Usually precision goes up and recall goes down.
  * Usually precision goes down and recall goes up.
  * Usually precision goes up or down depending on the dataset and recall stays constant.
  * Precision and recall move but we need to try this out on a concrete dataset to find out in what direction. Hard to tell upfront.
  * Precision and recall do not move because they are unrelated to the threshold. 

## Others

* TensorFlow?


* Programming for data scientists?


