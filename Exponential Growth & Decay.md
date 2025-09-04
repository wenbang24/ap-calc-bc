#APCalc 
#Math 
[[2025-01-18]]
Suppose$$
{dy\over dt}=\underbrace{k}_\text{constant of proportionality}\times y
$$
# Basic Law of Exponential Growth/Decay
$$
y=Ce^{kt}
$$
where:
- C is initial value (t = 0)
- k is constant of proportionality (k > 0 growth, k < 0 decay)
- t is time
- y is amount at time t
## Example
What is the rate of growth in a population where the population triples every 100 years?$$
\displaylines{P=Ce^{kt}\\\text{When }t=100,\,P=3C\\3C=Ce^{100k}\\3=e^{100k}\\\ln{3}=100k\\k={\ln{3}\over100}=0.0109861229=1.10\%}
$$
# Logistic Equations
[[2025-01-25]]
If the growth rate decreases as the population grows and there is a maximum population (carrying capacity) M, then$$
{dP\over dt}=kP(M-P)
$$The solution is of the form$$
P=\frac{M}{1+Ce^{-kMt}}
$$Note: C is **not** the initial amount here, you need to plug in an initial condition and solve for C