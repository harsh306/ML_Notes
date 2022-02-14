# Machine Learning basics

### Core Algorithms
- Descion Trees: [Link](https://towardsdatascience.com/understanding-decision-trees-for-classification-python-9663d683c952) 
- Linear Regression - Elements of Statistical Learning (pages 43-49)
  -  R-square vs Adjusted R-2 coefficient of determintation
  -  
- Logistic Regression [Link](https://docs.google.com/document/d/e/2PACX-1vTmmpP_tr2_11J0_wS64bcpl4w4Ey6VaJgBaZAOWYqKq2JGexMdirqoZf56BvfqgO5uYXXaqku8pecB/pub)
- Bagging vs Boosting and Stacking [Link](https://stats.stackexchange.com/questions/18891/bagging-boosting-and-stacking-in-machine-learning) [Link2](https://www.upgrad.com/blog/bagging-vs-boosting/#Why_is_bagging_better_than_boosting) 
- Gradient Boosting [Link](https://machinelearningmastery.com/gentle-introduction-gradient-boosting-algorithm-machine-learning/)
- Bayes Theorem [Link](https://betterexplained.com/articles/an-intuitive-and-short-explanation-of-bayes-theorem/)
- Naive Bayes [Link]()
- Descion Trees
- Random Forest (descion Trees + Bagging + random feature subset)
- K-NN [Link](https://towardsdatascience.com/machine-learning-basics-with-the-k-nearest-neighbors-algorithm-6a6e71d01761)
- K-means 
- SVM [Link](https://svmtutorial.online/download.php?file=SVM_tutorial.pdf) [Link2](https://www.svm-tutorial.com/category/svm-tutorial/math-svm-tutorial/)
- PCA and SVD computation from data matrix. [Link](https://www.youtube.com/watch?v=IbE0tbjy6JQ&list=PLBv09BD7ez_5_yapAg86Od6JeeypkS4YM) [Link](https://docs.google.com/document/d/e/2PACX-1vT9cGkZ8KFpt55t7fR3eB2BNrhKrmyT2joSR_1XMNmsPWsCs2g8YKK3EwhO4_3gsDirI3vCwJ6swPVb/pub)

### Imp ML Concepts
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
- 

### Statistics and Probability 
- Counting, Permutations, Combinations [Link](https://www.khanacademy.org/math/statistics-probability/counting-permutations-and-combinations/)
  - Permutations = n!/(n-r)! ; n is total number of objects and r is number of objects selected
  - Combinations = n!/{r!.(n-r)!} ; n is total number of objects and r is number of objects selected
  - Rule of product (src: wikipedia): In combinatorics, the rule of product or multiplication principle is a basic counting principle (a.k.a. the fundamental principle of counting). Stated simply, it is the intuitive idea that if there are a ways of doing something and b ways of doing another thing, then there are a · b ways of performing both actions. Example for first slot 5 options, for secod and third also 5. So there are total 5x5x5 ways of considering alll combinations. 
- Random variable [Link](https://www.khanacademy.org/math/ap-statistics/random-variables-ap/discrete-random-variables/)
  - X: Number of heads after tossing a coing 3 times
  - pdf: probability/number of heads(0,1,2,3)
- Descriptive Statistics
  - Sample Distribution [Link](https://www.khanacademy.org/math/ap-statistics/sampling-distribution-ap/what-is-sampling-distribution/v/introduction-to-sampling-distributions)
    - Population parameters (population mean, std, proportions) etc.
    - Take a random sample from this distribution  (sample mean, std dev etc)
    - Central limit theorem (as you take multiple samples more like infinite samples). Samples grows, plot it on frequency distribution y-axis freuency and x-axis sample means. It converges to normal distribution. It applies to means, sums and variance. 
    - This later becomes sampling distribution of sample mean or any statistics. 
- Distributions
  - Binomial Distribution (0,1)
  - Bernaulii Distribution (0, 1, 2, ..k)
  - Normal Distribution (Gaussian)
  - Uniform Distribution  ()
- Descriptive and Inferential Statistics 
- Hypothesis testing
  - p-value
  - pdf, pmf
  - Exact vs In-exact test
  - T-distribution vs z or Normal distribution
- Probablity 
  - Conditional Probability
  - Bayes Theorem
  - Interview Q/A [Link](https://github.com/kojino/120-Data-Science-Interview-Questions/blob/master/probability.md) [Link](https://www.nicksingh.com/posts/40-probability-statistics-data-science-interview-questions-asked-by-fang-wall-street)
- Statistical Tests to compare ML [Link](https://machinelearningmastery.com/statistical-significance-tests-for-comparing-machine-learning-algorithms/)
  - Significance Test to compare infernce  [Link1](https://machinelearningmastery.com/statistical-significance-tests-for-comparing-machine-learning-algorithms/)[Link2](https://machinelearningmastery.com/mcnemars-test-for-machine-learning/)


# Machine Learning General

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


