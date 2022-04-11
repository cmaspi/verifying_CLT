# Verifying CLT
### Authors
[Chirag Mehta](https://github.com/cmaspi),
[Dishank Jain](https://github.com/Dishank422),
[Datta](https://github.com/SavaranaDatta),
[Vishwanath](https://github.com/vishwanath-123)
## Introduction
We are testing whether CLT holds for various distribution or not. The distributions studied are listed as follows
1. Gaussian distribution
2. Uniform distribution
3. $\chi^2$ distribution
4. Cauchy distribution

## Method of Testing
We are creating a sample of size 100 from each distribution. CLT says that $\bar{X}$ follows a normal distribution with mean $\mu$ and variance $\sigma/10$. We make 1000 samples, then visualise it using various techniques listed below
1. Q-Q plot
2. histogram

We use other hypothesis testing techniques to verify that the distribution is indeed normal. We formulate our problem in the following way
- Alternate hypothesis: CLT doesn't hold
- Null hypothesis: CLT holds true

Here, type 2 error is when CLT is actually false but we fail to reject it. It is more dangerous because several models are built on the assumption that CLT is indeed correct. We will be using one or more of the following techniques
1. D'Agostino Pearson omnibus
2. Shapiro-wilk
3. Kolmogorov-Smimov

-------------------

If CLT is correct then $\bar{X}$ should follow normal distribution and it should have mean $\mu$ which is the sample as the original distribution we sampled it from. While, for the variance, we expect the variance to be $\sigma/10$. We will take only a large risk, perhaps like 0.95