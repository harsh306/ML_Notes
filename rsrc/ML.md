# Machine Learning basics

### Core Algorithms
- Descion Trees: [Link](https://towardsdatascience.com/understanding-decision-trees-for-classification-python-9663d683c952) 
  - Entropy or information gain to make the first split and so on.
- Random Forest (descion Trees + Bagging + random feature subset) [Link](https://www.youtube.com/watch?v=v6VJ2RO66Ag)
  - Reduces bias by overfiting one tree
  - Reduces variance by combining results from multiple trees (bagging)   
- Linear Regression - Elements of Statistical Learning (pages 43-49) and ISLR
  -  R-square vs Adjusted R-2 coefficient of determintation
  -  Regression analysis playlist [Link](https://www.youtube.com/playlist?list=PLTNMv857s9WUI1Nz4SssXDKAELESXz-bi)
  -  Multicolenarity [Link](https://www.youtube.com/watch?v=Cba9LJ9lS8s&list=PLTNMv857s9WUI1Nz4SssXDKAELESXz-bi&index=9)
- Logistic Regression [Link](https://docs.google.com/document/d/e/2PACX-1vTmmpP_tr2_11J0_wS64bcpl4w4Ey6VaJgBaZAOWYqKq2JGexMdirqoZf56BvfqgO5uYXXaqku8pecB/pub)
- Bagging vs Boosting and Stacking [Link](https://stats.stackexchange.com/questions/18891/bagging-boosting-and-stacking-in-machine-learning) [Link2](https://www.upgrad.com/blog/bagging-vs-boosting/#Why_is_bagging_better_than_boosting) 
- Gradient Boosting [Link](https://machinelearningmastery.com/gentle-introduction-gradient-boosting-algorithm-machine-learning/) [LINK2](https://www.youtube.com/watch?v=en2bmeB4QUo)
  - Is a error reducing strategy which can be used with any weak learner along with the idea of boosting. 
  - Linear regression or descion tree.  
- Bayes Theorem [Link](https://betterexplained.com/articles/an-intuitive-and-short-explanation-of-bayes-theorem/)
  - P(A|B) = P(B|A).P(A)/P(B)
- Naive Bayes [Link]()
- K-NN [Link](https://towardsdatascience.com/machine-learning-basics-with-the-k-nearest-neighbors-algorithm-6a6e71d01761)
  - KNN works by finding the distances between a query and all the examples in the data, selecting the specified number examples (K) closest to the query, then votes for the most frequent label (in the case of classification) or averages the labels (in the case of regression)
  - General rule is k = sqrt(N) 
- K-means [Link](https://medium.com/analytics-vidhya/how-to-determine-the-optimal-k-for-k-means-708505d204eb)
  - k points at ramdom, 
  - assign datapoints to center  
  - Recompute cluster center
  - move center and iterate
  - Elbow method: choose k based on sharp drop in sum of squared errors between center and data points as k increases. 
- SVM [Link](https://svmtutorial.online/download.php?file=SVM_tutorial.pdf) [Link2](https://www.svm-tutorial.com/category/svm-tutorial/math-svm-tutorial/)
- PCA and SVD computation from data matrix. [Link](https://www.youtube.com/watch?v=IbE0tbjy6JQ&list=PLBv09BD7ez_5_yapAg86Od6JeeypkS4YM) [Link](https://docs.google.com/document/d/e/2PACX-1vT9cGkZ8KFpt55t7fR3eB2BNrhKrmyT2joSR_1XMNmsPWsCs2g8YKK3EwhO4_3gsDirI3vCwJ6swPVb/pub)

### Imp ML Concepts
- Bias variance Tradeoff [Link](https://www.youtube.com/watch?v=EuBBz3bI-aA) [Link2](https://www.youtube.com/watch?v=YIPsfEtJppE)
  - Random Forest [Link](https://stats.stackexchange.com/questions/285866/why-does-a-bagged-tree-random-forest-tree-have-higher-bias-than-a-single-decis)
  - Low bias and variance is reducned by bagging. 
  - Linear regression is high bias , low variance (less complex model)
  - Full NN is low bias high variance (more complex model)
  - high Bias is mifit in training data 
  - high variance is difference in errors with different data set e.g. test data. 
- Correlation vs Causation [Link](https://www.iperceptions.com/blog/causation-vs-correlation)
- Pearson Correlation
- L1 and L2 Regularizer [Link](https://towardsdatascience.com/intuitions-on-l1-and-l2-regularisation-235f2db4c261) [Link2](https://explained.ai/regularization/index.html) [Link-Viz](https://simzhou.com/en/posts/2021/cross-entropy-loss-visualized/)
- Why cross entropy vs MSE [Link](https://www.youtube.com/watch?v=gIx974WtVb4)
- Dummy Variable Trap[Link](https://docs.google.com/document/d/e/2PACX-1vTCgloYD87WQK4zqqV0YwZpQuuB6etoGE-2n_AfBSwu9X4QDYIawpu-8Y44UL2xPKiZ2EWyQtPJnVFI/pub)
- My MLE-Notes[Link](https://github.com/harsh306/Notes-MLE/tree/master/pdf)
- Log-likelihood [Link](https://blog.metaflow.fr/ml-notes-why-the-log-likelihood-24f7b6c40f83) [Link2](https://ljvmiranda921.github.io/notebook/2017/08/13/softmax-and-the-negative-log-likelihood/)
  - StatQuest MLE [Link](https://www.youtube.com/watch?v=XepXtl9YKwc) 
  - Proabbility vs Likelihood [Link](https://www.youtube.com/watch?v=pYxNSUDSFH4)
  - Negative log likelihood and Cross Entropy [Link](https://glassboxmedicine.com/2019/12/07/connections-log-likelihood-cross-entropy-kl-divergence-logistic-regression-and-neural-networks/)
- Least Square Error [Link](https://towardsdatascience.com/ml-notes-why-the-least-square-error-bf27fdd9a721)
- Information Theory [Link](https://towardsdatascience.com/must-know-information-theory-concepts-in-deep-learning-ai-e54a5da9769d)
- Parametric and non-Parametric [Link](https://machinelearningmastery.com/parametric-and-nonparametric-machine-learning-algorithms/)
- ML FAQ [Link](https://sebastianraschka.com/faq/index.html)
- MLE vs MAP [Link](https://wiseodd.github.io/techblog/2017/01/01/mle-vs-map/)

### Evaluation
- Precion Recall , Accuracy, F1 Confusion Matrix [Link](https://www.youtube.com/watch?v=Kdsp6soqA7o)
- AUC ROC [Link](https://www.youtube.com/watch?v=4jRBRDbJemM) [Link](https://towardsdatascience.com/understanding-auc-roc-curve-68b2303cc9c5)




# Machine Learning Extras

### Type of Loss [link](https://gombru.github.io/2018/05/23/cross_entropy_loss/)

### Pairwise losses [link](https://gombru.github.io/2018/05/23/cross_entropy_loss/)

### Decision Trees and Cross Entropy [Link](https://docs.google.com/document/d/e/2PACX-1vTBOla5TwuUQbA6ZhrQi29f361Vl8-kUz_F9rA2jsl1DzAs_xoV5duoauUOovF2EoloVAtglku7wFib/pub)

### ISOMAP [Link](https://blog.paperspace.com/dimension-reduction-with-isomap/)

### Compressed Sensing [Link](https://github.com/dmh43/research/blob/master/theory_group/compressed_sensing/notes.pdf)

### SMOTE [Link](http://rikunert.com/SMOTE_explained)

### K-NN [Link](https://towardsdatascience.com/machine-learning-basics-with-the-k-nearest-neighbors-algorithm-6a6e71d01761)

### Stratified Sampling [Link](https://en.wikipedia.org/wiki/Stratified_sampling)

### Categorical data [Link](https://towardsdatascience.com/an-overview-of-categorical-input-handling-for-neural-networks-c172ba552dee)

### Covariate Shift in ML or Why train and test data should come from similar distribution [Link](https://towardsdatascience.com/how-dis-similar-are-my-train-and-test-data-56af3923de9b)

### Kalman_filter [Link](https://www.bzarg.com/p/how-a-kalman-filter-works-in-pictures/)


