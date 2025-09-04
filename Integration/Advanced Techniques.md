#APCalc 
#Math 
# Rational Functions
[[2024-11-23#Advanced Techniques]]
If integrating a [rational function](Useful%20Things.md#Rational%20Functions) where degree of numerator $\geq$ degree of denominator, use long division to 'split' the fraction
## Worked example
$$
\displaylines{\begin{array}{rl}
    \underline{\quad\quad\quad\quad\quad1} \\
    x^2+2 | x^2-4x+2 \\
      \underline{x^2\phantom{0000}+2} \\
      -4x\phantom{000}
  \end{array}\\\frac{x^2-4x+2}{x^2+2}=1-\frac{4x}{x^2+2}\\\int1-\frac{4x}{x^2+2}\,dx\\=x-\int\frac{4x}{x^2+2}\,dx\\\text{Let }u=x^2+2,du=2xdx,2du=4xdx\\=x-2\int\frac{du}{u}\\=x-2\ln|u|+C\\=x-2\ln(x^2+2)+C}
$$
# Integration by Parts
[[2024-12-07#Integration by parts]]
Mainly used for products of algebraic and transcendental functions or two transcendental functions.
$$
\displaylines{\int uv'\,dx=uv-\int vu'\,dx\\\text{Better version:}\\\int u\,dv=uv-\int v\,du}
$$
Note: you will find du when you take the derivative of u.
Get u and dv from the function, then differentiate u and integrate dv to find du and v.
## Picking u and v
Make u the part where the derivative is simpler or no more complicated.
Make dv (v') the part that is easily integrated.
Pick u according to this list (higher is better)
- **I**nverse trigonometric
- **L**ogarithmic
- **A**lgebraic
- **T**rigonometric
- **E**xponential
## Worked Examples
$$
\displaylines{\int xe^x\,dx\\u=x\,\text{(algebraic > exponential), }du=dx\\dv=e^xdx,v=e^x\\uv-\int v\,du\\=xe^x-\int e^x\,dx\\=xe^x-e^x+C}
$$$$
\displaylines{\int x\sin(3x)\,dx\\u=x,\,du=dx\\dv=\sin(3x)\,dx,\,v=-{1\over3}\cos(3x)\\uv-\int v\,du\\=-{1\over3}x\cos(3x)-\int-{1\over3}\cos(3x)\,dx\\=-{1\over3}x\cos(3x)-{1\over9}\sin(3x)+C}
$$
# Integration Using Partial Fractions
Sometimes you can split a single fraction into more to make integration easier.
## Worked Examples
$$
\displaylines{\int\frac{1}{x^2-7x+12}\,dx\\=\int\frac{1}{x-4}\frac{1}{x-3}\,dx\\=\int\frac{A}{x-4}+\frac{B}{x-3}\,dx\\1=A(x-3)+B(x-4)\\\text{Let }x=3\\1=B(3-4)\\B=-1\\\text{Let }x=4\\1=A(4-3)\\A=1\\=\int\frac{1}{x-4}-\frac{1}{x-3}\,dx\\=\ln|x-4|-\ln|x-3|+C}
$$
$$
\displaylines{\int\frac{5x-3}{(x-3)(x+1)}\,dx\\\frac{5x-3}{(x-3)(x+1)}=\frac{A}{x-3}+\frac{B}{x+1}\\5x+3=A(x+1)+B(x-3)\\\text{Let }x=-1,B=2\\\text{Let }x=3,A=3\\=\int\frac{3}{x-3}\,dx+\int\frac{2}{x+1}\,dx\\=3\ln|x-3|+2\ln|x+1|+C}
$$
## Interesting way to solve ? = A(x+?) + B(x+?)
Example:$$
\displaylines{2x+1=A(x-1)+B(x+2)\\2x+1=Ax-A+Bx+2B\\2x+1=(A+B)x+(-A+2B)\\2x=(A+B)x,2=A+B\\1=-A+2B\\3=3B\\B=1\\A=1}
$$
