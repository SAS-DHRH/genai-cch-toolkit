---
section: Definitions
nav_order: 3
title: Machine Learning
topics: machine learning; deep learning
---

## ℹ️ What is Machine Learning?  


Machine learning (ML) is a subfield of artificial intelligence,  that focuses on the use of data and algorithms to enable AI to imitate the way that humans learn, gradually improving its accuracy. ML is concerned with the development and study of statistical algorithms that can learn from data and generalize to unseen data and thus perform tasks without explicit instructions.


#### Types of machine learning

There are four basic types of machine learning: supervised learning, unsupervised learning, semisupervised learning and reinforcement learning.

 	  
- *Supervised machine learning* is defined by its use of labeled datasets to train algorithms to classify data or predict outcomes accurately. As input data is fed into the model, the model learns and grows more accurate over time. Both the input and output of the algorithm are specified in supervised learning. This occurs as part of the cross validation process to ensure that the model avoids overfitting or underfitting. Supervised learning helps organizations solve a variety of real-world problems at scale, such as classifying spam in a separate folder from your inbox. Some methods used in supervised learning include neural networks, naïve bayes, linear regression, logistic regression, random forest, and support vector machine (SVM).

- *Unsupervised machine learning*, uses machine learning algorithms to analyze and cluster unlabeled datasets (subsets called clusters). These algorithms discover hidden patterns or trends that can be used to group data points into subsets without the need for human intervention. This method’s ability to discover similarities and differences in information make it ideal for exploratory data analysis, cross-selling strategies, customer segmentation, and image and pattern recognition. It’s also used to reduce the number of features in a model through the process of dimensionality reduction. Principal component analysis (PCA) and singular value decomposition (SVD) are two common approaches for this. Other algorithms used in unsupervised learning include neural networks, k-means clustering, and probabilistic clustering methods.


- *Semi-supervised learning works by feeding a small amount of labeled training dataset to an algorithm to guide classification and* feature extraction from a larger, unlabeled data set. The performance of algorithms typically improves when they train on labeled data sets. Semi-supervised learning can solve the problem of not having enough labeled data for a supervised learning algorithm. It also helps if it’s too costly to label enough data. 


- *Reinforcement machine learning* is a machine learning model that is similar to supervised learning, but the algorithm isn’t trained using sample data. This model learns as it goes by using trial and error to take the best action by establishing a reward system. A sequence of successful outcomes will be reinforced to develop the best recommendation or policy for a given problem.


#### Machine learning algorithms


A number of machine learning algorithms are commonly used. These include:

- *Neural networks*: Neural networks  simulate the way the human brain works, with a huge number of linked processing nodes. Neural networks are good at recognizing patterns and play an important role in applications including natural language translation, image recognition, speech recognition, and image creation.

- *Linear regression*: This algorithm is used to predict numerical values, based on a linear relationship between different values. For example, the technique could be used to predict house prices based on historical data for the area.

- *Logistic regression*: This supervised learning algorithm makes predictions for categorical response variables, such as “yes/no” answers to questions. It can be used for applications such as classifying spam and quality control on a production line.

- *Clustering*: Using unsupervised learning, clustering algorithms can identify patterns in data so that it can be grouped. Computers can help data scientists by identifying differences between data items that humans have overlooked.


- *Decision trees*: Decision trees can be used for both predicting numerical values (regression) and classifying data into categories. Decision trees use a branching sequence of linked decisions that can be represented with a tree diagram. One of the advantages of decision trees is that they are easy to validate and audit, unlike the black box of the neural network.

- *Random forests*: In a random forest, the machine learning algorithm predicts a value or category by combining the results from a number of decision trees.




## ℹ️ What is Deep Learning? 



Deep learning is a subset of machine learning, which automates much of the feature extraction piece of the process, eliminating some of the manual human intervention required. It also enables the use of large data sets, earning the title of scalable machine learning.
Observing patterns in the data allows a deep-learning model to cluster inputs appropriately. A deep-learning model requires more data points to improve accuracy, whereas a machine-learning model relies on less data given its underlying data structure. 



#### What’s the difference between machine learning and deep learning ?


Since deep learning and machine learning tend to be used interchangeably, it’s worth noting the nuances between the two. Machine learning, deep learning, and neural networks are all sub-fields of artificial intelligence. However, neural networks is actually a sub-field of machine learning, and deep learning is a sub-field of neural networks.


The primary difference between machine learning and deep learning is how each algorithm learns and how much data each type of algorithm uses. "Deep" machine learning can use labeled datasets, also known as supervised learning, to inform its algorithm, but it doesn’t necessarily require a labeled dataset. The deep learning process can ingest unstructured data in its raw form (e.g., text or images), and it can automatically determine the set of features which distinguish different categories of data from one another. This eliminates some of the human intervention required and enables the use of large amounts of data. 

Classic or “nondeep” machine learning depends on human intervention to allow a computer system to identify patterns, learn, perform specific tasks and provide accurate results. Human experts determine the hierarchy of features to understand the differences between data inputs, usually requiring more structured data to learn.


## ℹ️ What are Neural networks?


Neural networks, also called artificial neural networks  (ANNs) or simulated neural networks, are a subset of machine learning and are the backbone of deep learning algorithms. They are called “neural” because they mimic how neurons in the brain signal one another. Neural networks are made up of node layers—an input layer, one or more hidden layers and an output layer. Each node is an artificial neuron that connects to the next, and each has a weight and threshold value. When one node’s output is above the threshold value, that node is activated and sends its data to the network’s next layer. If it’s below the threshold, no data passes along. Otherwise, no data is passed along to the next layer of the network by that node. The “deep” in deep learning is just referring to the number of layers in a neural network. A neural network that consists of more than three layers—which would be inclusive of the input and the output—can be considered a deep learning algorithm or a deep neural network. A neural network that only has three layers is just a basic neural network.

Neural networks are a commonly used, specific class of machine learning algorithms. Artificial neural networks are modeled on the human brain, in which thousands or millions of processing nodes are interconnected and organized into layers. In an artificial neural network, cells, or nodes, are connected, with each cell processing inputs and producing an output that is sent to other neurons. Labeled data moves through the nodes, or cells, with each cell performing a different function.

Training data teach neural networks and help improve their accuracy over time. Once the learning algorithms are fined-tuned, they become powerful computer science and AI tools because they allow us to quickly classify and cluster data. Using neural networks, speech and image recognition tasks can happen in minutes instead of the hours they take when done manually. Google’s search algorithm is a well-known example of a neural network.


#### What’s the difference between deep learning and neural networks?

As mentioned in the explanation of neural networks above, but worth noting more explicitly, the “deep” in deep learning refers to the depth of layers in a neural network. A neural network of more than three layers, including the inputs and the output, can be considered a deep-learning algorithm. 

Most deep neural networks are feed-forward, meaning they only flow in one direction from input to output. However, you can also train your model through back-propagation, meaning moving in the opposite direction, from output to input. Back-propagation allows us to calculate and attribute the error that is associated with each neuron, allowing us to adjust and fit the algorithm appropriately.


