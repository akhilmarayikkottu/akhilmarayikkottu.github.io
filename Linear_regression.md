### Linear regression

Let us assume that we have a noisy data sampled from a tru generator ```markdown $t = 10x+2$''' as shown in the figure below and previously used in the un-regularized linear regression. In this section, we try to give this MLE prediction a probabilistic overtone. We can assume that the output generated from the noisy generator follows a Gaussian conditional distribution $\mathcal{N} (t| \mu , \sigma)$, here the mean of the distribution is some function of the form $\mu = Ax+B$ where $A$ and $B$ are learning parameters and together the model form a class of functions. $\sigma$ is a learnable parameter which describes the spread of the datapoints with respect to the mean $\mu$.

