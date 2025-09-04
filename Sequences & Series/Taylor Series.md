wtf bro
#APCalc 
#Math 
[[2025-02-08#Taylor Series]]
# Taylor Polynomial
$$
P_n(x)=f(c)+f'(c)(x-c)+{f''(c)\over2!}(x-c)^2+{f'''(c)\over3!}(x-c)^3+\cdots+{f^{(n)}(c)\over n!}(x-c)^n
$$
This is an nth order Taylor Polynomial centered at c
$f(x)$ must have at least n derivatives ($x^2$ does not count since it becomes 0)
Higher order = better approximation
Infinite series = exactly correct
## c = 0: Maclaurin Polynomial
$$
P_n(x)=f(0)+f'(0)x+{f''(c)\over2!}x^2+{f'''(0)\over3!}x^3+\cdots+{f^{(n)}(0)\over n!}x^n
$$
# Taylor Series
$$
\displaylines{f(x)=f(c)+f'(c)(x-c)+{f''(c)\over2!}(x-c)^2+{f'''(c)\over3!}(x-c)^3+\cdots+{f^{(n)}(c)\over n!}(x-c)^n+\cdots\\f(x)=\sum_{n=0}^\infty{f^{(n)}(c)\over n!}(x-c)^n}
$$$f(x)$ must be infinitely differentiable at $x=c$
## Elementary Series
### sin x
$$
\sin(x)=x-{x^3\over3!}+{x^5\over5!}-\cdots+(-1)^n{x^{2n+1}\over(2n+1)!}+\cdots
$$
### cos x
$$
\cos(x)=1-{x^2\over2!}+{x^4\over4!}-\cdots+(-1)^n{x^{2n}\over(2n)!}+\cdots
$$
### e^x
$$
e^x=1+x+{x^2\over2!}+{x^3\over3!}+\cdots+{x^n\over n!}+\cdots
$$
### ln x
$$
\ln x=(x-1)-{(x-1)^2\over2}+{(x-1)^3\over3}-{(x-1)^4\over4}+\cdots+(-1)^{n-1}{(x-1)^n\over n}+\cdots
$$only for $0<x\leq2$