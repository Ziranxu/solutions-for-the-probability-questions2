# solutions-for-the-probability-questions2

1 Generate random sample size 100 from the distribution with density f(x) = 2exp(−2x),x ≥ 0. Check the feasibility of the obtained 
data using: histogram,mean, variance, EDF.

2 Generateasamplefromdoubleexponentialdistributionwithvariance1: f(x) =C*e^(−k|x|) ,−∞ < x < ∞. Implement accept-reject method 
to transform this sample into a sample from standard normal distribution. What is the resulting sample size? How does it confirm the
theoretical results?

3 Use Monte Carlo method with f(x) ∼ Exp(α) to evaluate integrals
        integral from 0 to inf (α*x*exp(−αx)*dx)
  and
        integral from 0 to inf (α*ln(x)*exp(−αx)*dx)
  for α = 3 and α = 4
  
 4 Generate a sample (x 1 ,...x n ),n = 100 from Poisson distribution X ∼Poiss(λ = 1.5). Then use it to estimate P(X > 2)
 
 5 Using Monte Carlo method with a generated sample x i ∼ Gamma(4,2),estimate integral
        integral from 0 to inf (x^5*exp(−2x)*dx)
   In order to generate a sample x i ∼ Gamma(4,2), apply:
(a) Representation of gamma distribution Gamma(4,2) as a sum of exponentials.
(b) Accept-reject technique with instrumental density Gamma(2,1).
Compare the results.

6 Use the method of antithetic variables to estimate E(X^2),X ∼ Unif[0,1]. Obtain exact numerical value for the variance Var(h2n),
h(x) = x^2 and compare it with the simulation results (suggested use of 100 simulations with n =100).
