# Deep Learning Basics [Quick reads]

#### Prerequisites 
- Linear Algebra and Calculus
- Intro to Probability
- Entropy and information
- Loss Functions
- Maximum Likelihood Estimate


#### Gradient Descent and Optimization [Link1](https://docs.google.com/document/d/e/2PACX-1vSRkLjI5Kpt8dPyN5wylb1ZgkdhzKTv21MrRIWktbOymwHzHOLXzxer4K57jnVmSa5kybLieV8Lc4CF/pub) [Link2](https://docs.google.com/document/d/e/2PACX-1vQmomWlyGsNQUyvBHRK6YMhiLJ6ee0PWPG4hZZyLRFHFE412lZgO5qHZ7iUkxltM0rxhJ8uf79bZSSk/pub)
- Taylor Series Approximation [Link](https://suzyahyah.github.io/calculus/optimization/2018/04/06/Taylor-Series-Newtons-Method.html)
- Momentum [Link](https://distill.pub/2017/momentum/)

#### Backpropagation and Initializations 
- Xavier/Glorot [Link](https://www.deeplearning.ai/ai-notes/initialization/)
- He init [Link](https://medium.com/@shoray.goel/kaiming-he-initialization-a8d9ed0b5899)
- Softmax CrossEntropy Backprop [Link](https://www.ics.uci.edu/~pjsadows/notes.pdf)
- RNN Backprop
- Attention Backprop
- Activations and differentiations

#### Unsupervised Pre-training, Fine-tuning[Link](https://www.youtube.com/watch?v=Oq38pINmddk)

#### Types of Network:
- Convolutional Neural Networks [Link](https://docs.google.com/document/d/e/2PACX-1vRG_-7Xe6DTwg-yfwPmYMoezS8WDYpWjC7jTnQeJnA4dDAiXlLBHwgkzQl_j-fCpZQTmuYU99ePGXww/pub)
- LSTMs, GRUs and RNNs
- Autoencoder, PCA 
- GANs [Link](https://www.youtube.com/watch?v=Gib_kiXgnvA) [Link](https://lilianweng.github.io/lil-log/2017/08/20/from-GAN-to-WGAN.html)
- Transformer and attention [Link](https://lilianweng.github.io/lil-log/2018/06/24/attention-attention.html)
- Why a deeper network? [Link](https://stats.stackexchange.com/questions/222883/why-are-neural-networks-becoming-deeper-but-not-wider) [Link2](https://stats.stackexchange.com/questions/222883/why-are-neural-networks-becoming-deeper-but-not-wider)

#### Regularizations 
- Dropouts [Link](https://medium.com/@bingobee01/a-review-of-dropout-as-applied-to-rnns-72e79ecd5b7b)
  - The core concept of Srivastava el al. (2014) is that “each hidden unit in a neural network trained with dropout must learn to work with a randomly chosen sample of other units. This should make each hidden unit more robust and drive it towards creating useful features on its own without relying on other hidden units to correct its mistakes.”. “In a standard neural network, the derivative received by each parameter tells it how it should change so the final loss function is reduced, given what all other units are doing. Therefore, units may change in a way that they fix up the mistakes of the other units. This may lead to complex co-adaptations. This in turn leads to overfitting because these co-adaptations do not generalize to unseen data.” Srivastava et al. (2014) hypothesize that by making the presence of other hidden units unreliable, dropout prevents co-adaptation of each hidden unit. 
     
- L1
- L2

#### Common Problems and Intuitions
- Best practice [Andrej](http://karpathy.github.io/2019/04/25/recipe/)
- Vanishing Gradients [Link](https://machinelearningmastery.com/how-to-fix-vanishing-gradients-using-the-rectified-linear-activation-function/) [Link2](https://towardsdatascience.com/the-vanishing-gradient-problem-69bf08b15484)
- Exploding Gradients [Link](https://www.machinecurve.com/index.php/2019/09/16/he-xavier-initialization-activation-functions-choose-wisely/)
- Batch Normalization [Link](https://towardsdatascience.com/batch-norm-explained-visually-how-it-works-and-why-neural-networks-need-it-b18919692739)
  - Covariate shift in inputs [Link](https://www.youtube.com/watch?v=nUUqwaxLnWs)
  - Faster convergence: Then during gradient descent, in order to “move the needle” for the Loss, the network would have to make a large update to one weight compared to the other weight. This can cause the gradient descent trajectory to oscillate back and forth along one dimension, thus taking more steps to reach the minimum. 
  - Vanishing exploding gradients
- Skip Connections, ResNets [Link](https://www.youtube.com/watch?v=RYth6EbBUqM) [ResNet](https://www.youtube.com/watch?v=ahkBkIGdnWQ)
  - skip connections allow the gradient to reach beginning weights with greater magnitude by skipping some layers in between.
- Modal Collapse in GANs [Link]()
- Data Augment [Stanford](https://stanford.edu/~shervine/teaching/cs-230/cheatsheet-deep-learning-tips-and-tricks) 


# Deep Learning General 

#### [https://www.deeplearningbook.org/](https://www.deeplearningbook.org/)

#### Practical Deep Learning [Link](http://course.fast.ai/lessons/lessons.html)

#### Deep Learning Optimization [Link](https://github.com/harsh306/awesome-nn-optimization)

#### Structuring Your Tensorflow Models [Link](https://danijar.com/structuring-your-tensorflow-models/)

#### AUTODIFF [Link](http://videolectures.net/deeplearning2017_johnson_automatic_differentiation/)  [JAX](https://colinraffel.com/blog/you-don-t-know-jax.html)

#### Self-supervised Learning [Link](https://arxiv.org/abs/2304.12210)


