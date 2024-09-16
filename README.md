java c
STAT 536: Homework 1 
Due September 20, 2024 
This home work should be done independently. Discussions with others are encouraged, however the code and output should be your own work. Please submit your work on Canvas (.rmd and .pdf files).
Q1. If X is a Binomial(n, p) random variable. Show that i) E(X) = np and V ar(X) = np(1 − p).
Q2. Derive the maximum likelihood estimates for the following
a. The mean parameter λ of an exponential distribution Exp(λ).
b. The mean parameter µ of a normal distribution N (µ, σ2), when σ2is known.
Q3. If F− represents the generalized inverse of a cdf F, i.e.,
F−(u) = inf {x ; F(x) ≥ u}
then show that following two sets are equivalent
{(u, x) ; F−(u) ≤ x} = {(u, x) ; F(x) ≥ u}	 .
Q4. [R] a) Recall that Z ∼ Binomial(n, p) can be expressed as a sum of n independent Bernoulli (p) random variables, i.e., Z =Pni =1 Xi, with Xi ∼ Ber(p). Use this result to simulate 1000 realizations of a Binomial (n = 3, p = 0.25) distribution. Do not print out the generated numbers, instead plot a bar chart of the values obtained.
Q5. [R] Use the transformation method to generate 1000 Gamma(4, 1) random deviates.Do not print out the generated 代 写STAT 536: Homework 1 2024C/C++
代做程序编程语言numbers, instead plot a histogram of the values obtained along with the density curve (both on the same plot).
Q6. If X ∼ Gamma(α, λ) and Y ∼ Gamma(β, λ) are independent, then Z = X+Y/X ∼ Beta(α, β) and is independent of X + Y ∼ Gamma(α + β, λ)
Q7. 
a. [R] Recall that X ∼ Exp(λ) ∼ Gamma(1, λ). Use this result together with that of Q6 to generate 1000 realizations of a Beta(2, 2) distribution.
b. Alternatively, one can implement the accept-reject method. Consider the instrumental variable Y to be such that Y ∼ U[0, 1] Then, develop the Accept-Reject method completely for generating a random sample of size n from X ∼ Beta(c + 1, c + 1) for any c > 0.
Q8. 
a. [R] Simulate 1000 random variables distributed as N (µ = 3, σ2 = 4) using the Box-Mueller transform. Plot a histogram of the values obtained along with the density curve
b. [R] Repeat part (a) using the Marsaglia’s polar method. Plot a histogram of the values obtained along with the density curve
Q9. Let X ∼ Gamma(a, b), choosing the instrumental variable Y as Y ∼ Exp(λ) derive the accept-reject method completely. Also, derive the optimal value of λ.







         
加QQ：99515681  WX：codinghelp
