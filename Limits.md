#Math
#APCalc 
[[2024-09-22]]
First, try substitution.
If a limit goes to an indeterminate form (e.g. $0/0$) then use algebraic techniques to change the form of the limit:$$\displaylines{\lim_{x\rightarrow0}{x\over x(x+1)}={0\over0}\\{x\over x(x+1)}={1\over x+1}\\\lim_{x\rightarrow0}{1\over x+1}={1\over1}=1}$$If this doesn't work, try a table:$$\lim_{x\rightarrow2^+}{x\over x-2}$$$$\begin{array} {|r|r|}\hline x & 2.1 & 2.01 & 2.001 & 2.0001 & 2.00001 & 2 \\ \hline {x\over x-2} & 21 & 201 & 2001 & 20001 & 200001 & \infty \\ \hline  \end{array}$$
# Intermediate Value Theorem
Intermediate value theorem [[2024-09-22]]:
If $f$ is continuous on $[a, b]$, and $k$ is any y value between $f(a)$ and $f(b)$, then there is at least one x value $c$ between $a$ and $b$ such that $f(c)=k$.
# Horizontal Asymptotes
[[2024-09-22]]
$$\displaylines{\lim_{x\rightarrow \infty}\frac{5x^4+3x^2+2}{10x^4+3}\\\lim_{x\rightarrow \infty}\frac{5x^4+3x^2+2}{10x^4+3}\times\frac{1\over x^4}{1\over x^4}\\\lim_{x\rightarrow \infty}\frac{5+{3\over x^2}+{2\over x^4}}{10+{3\over x^4}}\\\lim_{x\rightarrow \infty}\frac{5+{3\over \infty}+{2\over \infty}}{10+{3\over \infty}}\\\lim_{x\rightarrow \infty}\frac{5+0+0}{10+0}\\={1\over2}}$$However, to simplify things, we only need to consider the highest degree terms [[#Relative Growth Rates]]:$$\displaylines{\lim_{x\rightarrow \infty}\frac{(2x+1)(x+1)^2}{(x-1)(3x+2)^2}\\\lim_{x\rightarrow \infty}\frac{2x^3}{9x^3}\\={2\over9}}$$And with radical functions:$$\displaylines{\lim_{x\rightarrow -\infty}\frac{\sqrt{4x^2-3}}{x}\\\lim_{x\rightarrow -\infty}\frac{\sqrt{4x^2}}{x}\\\lim_{x\rightarrow -\infty}2\frac{|x|}{x}\\=-2}$$
## Asymptotes
[[2024-09-22]] (examples here)
If an asymptote is even, then $\lim_{x\rightarrow c}f(x)=\infty \text{ or }-\infty$. Both sides of the asymptote go in the same direction. This can happen when something in the denominator has an even power, or is an absolute value.
If an asymptote is odd, then, each sides goes in different directions. This can happen when something in the denominator has an odd
power (including 1).

[[2024-09-29]]
Oblique asymptote happens when highest power in numerator is one greater than higher power in denominator. It slowly approaches a line with the slope of the quotient of the coefficients. $$f(x)=\frac{3x^3+5x}{2x^2}\text{ has oblique asymptote at }y={3\over2}x$$
# L'Hôpital's Rule
[[2024-10-26]]
$$\text{If }\lim_{x\rightarrow c}f(x)=0\text{ and } \lim_{x\rightarrow c}g(x)=0\text{, or if both limits go to }\pm\infty\text{, then }\lim_{x\rightarrow c}\frac{f(x)}{g(x)}=\lim_{x\rightarrow c}\frac{f'(x)}{g'(x)}$$Must be in indeterminate form: $0\over0$ or $\pm\infty\over\pm\infty$. It can be used multiple times in succession.
## Other types of indeterminate form
[[2024-10-26#More Indeterminate Forms]]
$$0^0,\infty^0,1^\infty$$$0^\infty$ is not indeterminate.
Differentiate by adding a new variable $y = \lim_{x\rightarrow c}f(x)$, take the natural log of both sides, move the exponent out, solve for the limit (so you now have $\ln(y) = k$) and solve for y.
Example:$$\displaylines{\lim_{x\rightarrow \infty}x^{1\over x}\\\text{Let }y=\lim_{x\rightarrow \infty}x^{1\over x}\\\ln y=\lim_{x\rightarrow \infty}\ln(x^{1\over x})\\\ln y=\lim_{x\rightarrow \infty}{\ln x\over x}\\\ln y=\lim_{x\rightarrow \infty}{(\ln x)'\over x'}\\\ln y=\lim_{x\rightarrow \infty}{{1\over x}\over 1}\\\ln y=0\\y=1\\\therefore\lim_{x\rightarrow \infty}x^{1\over x}=1}$$
## Relative Growth Rates
If you are working with $x\rightarrow\pm\infty$, then you can use relative growth rates:$$1<\ln x<x<x^n<e^x$$