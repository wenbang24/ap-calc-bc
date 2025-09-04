#Math 
#APCalc 
# Alternating Series Remainder
[[2025-02-22#Alternating Series Remainder]]
For converging alternating series when approximating the sum of series by using only the first n terms, the error will be less than or equal to the absolute value of the n + 1st term. $$
\left|\sum_{k=1}^\infty(-1)^kf(x)-\sum_{k=1}^n(-1)^kf(x)\right|\leq f(n+1)
$$If k = 0, then upper bound is n - 1 and error is less than or equal to nth term.$$
\text{Alternating Series Remainder}\leq\left|\frac{f^{(n+1)}(c)(x-c)^{n+1}}{(n+1)!}\right|
$$
# Non-alternating Series Remainder
[[2025-02-22#BRO its f * *ing Lagrange ('s remainder for non-alternating series)]]$$
\text{Lagrange Remainder}\leq\left|\frac{f^{(n+1)}(z)(x-c)^{n+1}}{(n+1)!}\right|
$$Where $z$ is the x-value between x and c inclusive where $|f^{(n+1)}(z)|$ is maximum.
(yes that is the n+1st derivative of f)

$x$ is the value you are plugging in to the series function
$c$ is where the series is centered around (0 for maclaurin series)
$n$ is the number of terms you use