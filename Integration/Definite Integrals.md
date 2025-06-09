#APCalc 
#Math 
[[2024-11-23]]
# Definition
The area between the x-axis and curve of $f(x)$ between a and b:
$$\int_a^bf(x)dx$$
Can be positive, negative, or 0
# Solving with u-substitution
You need to convert the bounds integral into u and use those bounds instead
## Worked example:
$$\displaylines{\int_0^1(4t+1)^5dt\\\text{Let }u=4t+1,{du\over4}=dt\\\text{When }t=0,u=1; t=1,u=5\\\int_1^5u^5\times{1\over4}du\\={u^6\over24}|^5_1\\={1\over24}(5^6-1^6)\\=651}$$
# Infinite Riemann Sums
[[2024-12-07#Infinite Riemann Sum]]
$$\int_a^bf(x)\,dx=\lim_{n\rightarrow\infty}\sum_{k=1}^n(f(a+k\Delta x)\Delta x)=\lim_{n\rightarrow\infty}\sum_{k=1}^n(\underbrace{f(a+k{b-a\over n})}_\text{right hand heights}\underbrace{b-a\over n}_\text{width})$$
For right Riemann sums, the summation is from 1 to n.
For left Riemann sums, the summation is from 0 to n-1.