# Machine-Learning-Algorithms
Types of Machine Learning Algorithms There are 3 types of machine learning (ML) algorithms: 

Supervised Learning Algorithms: Supervised learning uses labeled training data to learn the mapping function that turns input variables (X) into the output variable (Y). In other words, it solves for f in the following equation:  Y = f (X) This allows us to accurately generate outputs when given new inputs.

We’ll talk about two types of supervised learning: 

classification and regression.

Classification is used to predict the outcome of a given sample when the output variable is in the form of categories. A classification model might look at the input data and try to predict labels like “sick” or “healthy.” 

Regression is used to predict the outcome of a given sample when the output variable is in the form of real values. For example, a regression model might process input data to predict the amount of rainfall, the height of a person, etc.

The first 5 algorithms – 
Linear Regression, 
Logistic Regression, 
CART, 
Naïve-Bayes, 
and K-Nearest Neighbors (KNN) 
    — are examples of supervised learning. 
    Ensembling is another type of supervised learning. It means combining the predictions of multiple machine learning models that are individually weak to produce a more accurate prediction on a new sample.
    Algorithms 9 and 10 of this article — Bagging with Random Forests, Boosting with XGBoost — are examples of ensemble techniques.
    
Unsupervised Learning Algorithms: 
   Unsupervised learning models are used when we only have the input variables (X) and no corresponding output variables. They use unlabeled training data to model the underlying structure of the data.  
   
   We’ll talk about three types of unsupervised learning:  
      Association is used to discover the probability of the co-occurrence of items in a collection. It is extensively used in market-basket analysis. For example, an association model might be used to discover that if a customer purchases bread, s/he is 80% likely to also purchase eggs. 
     
   Clustering is used to group samples such that objects within the same cluster are more similar to each other than to the objects from another cluster.  Dimensionality Reduction is used to reduce the number of variables of a data set while ensuring that important information is still conveyed. Dimensionality Reduction can be done using Feature Extraction methods and Feature Selection methods. Feature Selection selects a subset of the original variables. Feature Extraction performs data transformation from a high-dimensional space to a low-dimensional space.
   
   Example: PCA algorithm is a Feature Extraction approach.  Algorithms 6-8 that we cover here — Apriori, K-means, PCA — are examples of unsupervised learning.
  
  Reinforcement learning:
   Reinforcement learning is a type of machine learning algorithm that allows an agent to decide the best next action based on its current state by learning behaviors that will maximize a reward.  Reinforcement algorithms usually learn optimal actions through trial and error. Imagine, for example, a video game in which the player needs to move to certain places at certain times to earn points. A reinforcement algorithm playing that game would start by moving randomly but, over time through trial and error, it would learn where and when it needed to move the in-game character to maximize its point total.
