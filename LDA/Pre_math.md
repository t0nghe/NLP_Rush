# Pre Math Knowledge

## Binomial distribution
In general, if the random variable X follows the binomial distribution with parameters n ∈ ℕ and p ∈ [0,1], we write X ~ B(n, p). The probability of getting exactly k successes in n trials is given by the probability mass function:
$$f(k,n,p)=Pr(k;n,p)=Pr(X=k)=\binom{n}{k} p^k(1-p)^{n-k}$$

$$\binom{n}{k} = \frac{n!}{k!(n-k)!}$$

## Gamma function
for any positive integer n:
$$\Gamma(n)=(n-1)!$$

for complex numbers with a positive real part the gamma function is defined via a convergent improper integral:
$$\Gamma(z) = \int_{0}^{\infty}x^{z-1}e^{-x}dx\qquad z > 0$$

> The gamma function can be seen as a solution to the following interpolation problem:

> "Find a smooth curve that connects the points (x, y) given by y = (x − 1)! at the positive integer values for x."

![Gamma function](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b9/Factorial_Interpolation.svg/1920px-Factorial_Interpolation.svg.png)

## Beta distribution

### Probability density function
The probability density function (pdf) of the beta distribution, for 0 ≤ x ≤ 1, and shape parameters α, β > 0, is a power function of the variable x and of its reflection (1 − x) as follows:

$$f(x;\alpha,\beta)=constant*x^{\alpha-1}(1-x)^{\beta-1} = \frac{x^{\alpha-1}(1-x)^{\beta-1}}{\int^1_0 u^{\alpha-1}(1-u)^{\beta-1}du} =\frac{\Gamma(\alpha+\beta)}{\Gamma(\alpha)\Gamma(\beta)}x^{\alpha-1}(1-x)^{\beta-1}=\frac{1}{B(\alpha,\beta)}x^{\alpha-1}(1-x)^{\beta-1}$$