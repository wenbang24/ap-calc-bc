#Math
#APCalc
# First principle
[[2024-10-12]]
$$
f'(x)=\lim_{\Delta x\rightarrow0}\frac{f(x+\Delta x)-f(x)}{\Delta x}
$$
## Alternate form for solving at single point
$$
f'(c)=\lim_{x\rightarrow c}\frac{f(x)-f(c)}{x-c}
$$
# Product Rule
$$
{d\over dx}(f(x)\times g(x))=f'(x)g(x)+f(x)g'(x)\text{ or }{d\over dx}(f\times g)=fg'+f'g
$$
For more than 2 functions, differentiate one by one:$$
{d\over dx}fgh=f'gh+fg'h+fgh'
$$
# Quotient Rule
$$
{d\over dx}\left({f(x)\over g(x)}\right)=\frac{f'(x)g(x)-f(x)g'(x)}{g(x)^2}\text{ or }{d\over dx}\left({f\over g}\right)=\frac{f'g-fg'}{g^2}
$$
# Chain Rule
$$
{d\over dx}f(g(x))=f'(g(x))\times g'(x)
$$
For more than 2 functions, take derivates from the outside in and multiply:$$
{d\over dx}h(f(g(x)))=h'(f(g(x)))\times f'(g(x))\times g'(x)
$$
# Mean Value Theorem
[[2024-11-02#Mean Value Theorem]]
For all a < b, where $f: [a,b] \rightarrow\mathbb{R}$ is differentiable on $[a,b]$, there exists some c such that:$$
f'(c)=\frac{f(b)-f(a)}{b-a}
$$The secant line between a and b is tangent to the tangent line through c.