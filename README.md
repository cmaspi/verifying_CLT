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
3. geometric distribution
4. Cauchy distribution

## Method of Testing
We are generating 1000 bacthes of size 10, 30, 50, 100 from each distribution. CLT says that $\bar{X}$ follows a normal distribution with mean $\mu$ and variance $\sigma/10$. We are visualising it using various techniques listed below
1. histogram

We use other hypothesis testing techniques (frequentist tests) to verify that the distribution is indeed normal. We formulate our problem in the following way
- Alternate hypothesis: empirical approximation of the CLT doesn't hold
- Null hypothesis: empirical approximation of the CLT holds

We will be using the following technique
1. Shapiro-wilk

Note there are several other frequentist tests such as D'Agostino Pearson omnibus or Kolmogorov-Smimov, but shapiro wilk is the most popular one, and it gives more accurate results.

-------------------

If CLT is correct then $\bar{X}$ should follow normal distribution and it should have mean $\mu$ which is the sample as the original distribution we sampled it from. While, for the variance, we expect the variance to be $\sigma/\sqrt{n}$.