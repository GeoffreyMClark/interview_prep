# Machine Learning / Robotics Interview Prep
This file is a compilation of interview prep for Geoffrey Clark covering a range of topics including: statistics, math, machine learning, optimization, and deep neural networks. There will obviously be some overlap in these categories however I will endevor to do my best to sort each question into a usefull section. For each question I add an explanation and math/code if applicable. Please let me know if you have any questions or additional questions you would like me to add.

## How to answer questions
* concise answers
* Answer What, How and Why --which generally correspond with, visual explanation, analitical explanaton, and application focused explanation.

## Mathematics
1. What is an derivative? 

A derivative is how one variable changes based on very small changes in one or more other variables, and is best described as the tangent line of the function. The derevative is calculated with the limit as h->0 of f(x+h)-f(x)/h. Derivatives are necessary in many ways for machine learning most notably when calculating the backpropogation gradients for neural networks.

2. What is a intergral?
3. What is a gradient
4. Explain Eigen vectors and Eigenvalues



## Statistics
1. What is marginalization?
2. What is Bayes' Theorem?
3. What is the law of large numbers?
4. State the differnces between causality and correlation.
5. What is the difference between probability and likelihood?
6. What is KL-Divergence?
7. Why is KL-Divergence not a distance measure?
8. How does KL-Divergence relate the NLL?
9.  What is the difference between entropy and information gain?
10. What is Heteroscendasiticity?
11. How are standard deviation and variance related?
12. What is an ARIMA model and what are its components?
13. Important distributions
    1.  binomial
    2.  uniform
    3.  normal
    4.  poisson
    5.  exponential
    6.  von-Mises


## AI / ML
1. What is the difference between generative and discriminative models?
2. What are parametric and non-parametric models?
3. What is cross-calidation?
4. What is Bias in machine learning?
   * What is the bias Variance tradeoff?
   * Define and explain the concept of Inductive bias.
5. Explain the difference Between classification and regression.
6. Define Precision and Recall as they relate to classification?
7. What is a confusion matrix and why do you need it?
8. What is the difference between Type I and Type II error?
9.  What is the difference between accuracy and precision?
10. What are overfitting and underfitting, how do you solve each of these problems?
11. Explain Correlation and covariance.
12. Explain the “Curse of Dimensionality”.
13. What is regularization?
14. What is normalization?
15. What is standardization?
16. What are some exploratory data analysis (EDA) techniques?
   * Visualization
   * Missing value treatment
   * Outlier detection
   * Scaling
   * Feature engineering
   * Dimensionality reduction
17. How do you handle outlier values?
   * Discover: Box plot, Z-score, scatter plot
   * Solutions: drop them, mark them as outliers, and include, transform the feature to reduce the effect of outliers.
18. How do you handle missing or corrupted data in a dataset?
19. How is batch training accomplished?
20. What are some popular cross validation techniques?
   * K fold, stratified k fold, leave one out, bootstrapping, random search cv, grid search cv
21. What are some popular cross validation techniques?
   * K fold, stratified k fold, leave one out, bootstrapping, random search cv, grid search cv
22. What is Maximum Likelihood Estimation?
23. What are some different types of classes of machine learning algorithms?
   1. Supervised (task-driven)
      * Classicifation, Regression, Ranking
      * SVM, Naive Bayes, Decision Trees, K-nearest Neighbor, NN
   2. Unsupervised (data-driven)
      * Clustering, Segmentation, Dimensionality Reduction / Latent Variable Models
      * K-means, PCA, SVD, GMM
   3. Reinforcement learning
      * Rewaed Systems, Decision Proceses
      * Q-learning, R-learning, TD-Learning
   4. Self-supervised learning
   5. Semi-supervised learning
   6. Active Learning
24. What is ensemble learning?
   * Examples: Bagging, Boosting
25. Why is boosting more stable than other ensemble algorithms?
26. What are ensemble models? How do ensemble techniques yield better learning?
27. What is a Random forest, how does it work?
28. Can logistic regression be used for more than 2 classes?
29. What is linear regression?
30. What are Kernels in SVM? What is the Kernel trick?



   















