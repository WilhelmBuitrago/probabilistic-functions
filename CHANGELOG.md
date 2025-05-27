# 0.4.10
## 2025-05-23
### Add
  - Bernoulli, Binomial, Poisson, Geometric, Hypergeometric, Uniform, Normal, Exponential, Weibull, Gamma, Beta, Lindley, Gumbel, and Pareto Type I and II work correctly
  - Pareto Type VI (generalized) may have errors.
  - Log-Normal and Burr are not correctly implemented.
  - Pareto Types III, IV, V, etc., are not implemented
  - Only the PMF or PDF (depending on the distribution) and the MGF (closed or not) are implemented.
  - The CDF, survival function, and hazard function are not yet implemented but will be added.
  - The replace function may not work as expected.

# 0.4.11
## 2025-05-27
  - The distributions: Bernoulli, Binomial, Geometric, Hypergeometric, Poisson, Uniform, Exponential, Normal, Weibull, Gamma, Beta, LogNormal, and Gumbel
    * All have PDF/PMF, FGM (closed-form or not), CDF, SF (survival function), HF (hazard function)
    * They provide a summary of their characteristics when using the call method (Function()() or equivalents)
    * The replace function for these distributions works as expected
  - The Birnbaum-Saunders distribution may not function correctly
  - The remaining distributions have not been modified since the previous update (Burr types 1 and 2, Pareto types 1, 2, and 6, Lindley, etc)


