## Chapter 1: The Machine Learning Landscape
(ML is an acronym for Machine Learning)

What is Machine Learning?
Machine Learning is the science and art of programming computers so they can learn form data. 

OR 

We can say that Machine Learning is the field of study that gives computers the ability to learn without being explicitly programmed (By: Arthur Samuel, 1959)

OR (More engineering-oriented)

A computer program is said to learn from experience E with respect to some task T and some performance measure P, if its performance on T, as measured by P, improves with experience E. (By: Tom Mitchell, 1997)

**Example**: One of the oldest example of ML application is OCR (Optical Character recognition) and Spam filter.

What is Machine Learning great for?
* Problems for which existing solutions require a lot of hand-tuning or long lists of rules: one Machine Learning algorithm can often simplify code and perform better.
* Complex problems for which there is no good solution at all using a traditional approach: the best Machine Learning techniques can find a solution.
* Fluctuating environments: a Machine Learning system can adapt to new data.
* Getting insights about complex problems and large amounts of data.

#### Types of Machine Learning Systems

There are three bases on which we can classify the ML systems.

1. Whether or not they are trained with human supervision (Supervised, unsupervised, Semi-supervised and reinforcement learning) - Type 1
2. Whether or not they can learn incrementally on fly (Online versus batch learning) - Type 2
3. Whether they work by simply comparing new data points to known data points, or instead detect patterns in the training data and build a predictive model, much like scientists do (instance-based versus model-based learning) - Type 3

##### Type 1

**Supervised Learning**

In supervised learning along with the trainig data we provide the labels. These labels help us to supervise our trainig procedures. We use supervised learning for classification and regression tasks. (these terms will be explained later)

Example: Spam filter, house price predictions

Supervised Learning Algorithms:
* k-Nearest Neighbors
* Linear Regression
* Logistic Regression
* Support vector Machines (SVMs)
* Decision Trees and Random Forests
* Neural Networks

**Unsupervised Learning**

In Unsupervised learning the training data does not have the labels or we can say the training data is unlabeled. 

Unsupervised Learning Algorithms:
* Clustering
    * K-means
    * DBSCAN
    * Hierarchical Cluster Analysis (HCA)
* Anomaly Detection and novelty detection
    * One-class SVM
    * Isolation forest
* Visualization and dimensionality reduction
    * Principal Component Analysis (PCA)
    * Kernel PCA
    * Locally-Linear Embedding (LLE)
    * t-distributed Stochastic Neighbor Embedding (t-SNE)
* Association rule Learning
    * Apriori
    * Eclat

*Do not fear, we will cover all these topics gradually in later chapters*

**Semi-Supervised Learning**

Some algorithms can deal with partially labeled training data, usually a lot of unlabeled data and a little bit of labeled data. This is called semisupervised learning. Most semisupervised learning algorithms are combinations of nsupervised and supervised algorithms. For example, deep belief networks (DBNs) are based on unsupervised components called restricted Boltzmann machines (RBMs) stacked on top of one another.

Some photo-hosting services, such as Google Photos, are good examples of semi-supervised learning.

**Reinforcement Learning**

Reinforcement Learning is a very different beast. The learning system, called an agent in this context, can observe the environment, select and perform actions, and get rewards in return (or penalties in the form of negative rewards). It
must then learn by itself what is the best strategy, called a policy, to get the most reward over time. A *policy* defines what action the agent should choose when it is in a given situation.