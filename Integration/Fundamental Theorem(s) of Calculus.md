#APCalc 
#Math
[[2024-11-23]]
# FTOC
$$\displaylines{\int_a^bf'(x)dx=f(b)-f(a)=f(x)|^b_a\\\text{Note: }\int f'(x)dx=f(x)}$$
Refer to [[Definite Integrals#Definition]].
## Finding f(b)
### Accumulation Method
This is if you don't know C, and you are given f(a) and f'(x)
$$f(b)=f(a)+\int_a^bf'(x)dx$$
### Finding the Function
If you are given the derivative and a point just find the function
$$f(x)=\int f'(x)dx$$
# 2nd FTOC
For any constant a where $f$ is continuous from a to x,$${d\over dx}\int_u^vf(t)\,dx=f(v)v'-f(u)u'$$
## Worked Example of Usage
$$\displaylines{\int_0^{x^2}f'(t)dt=f(x^2)-f(10)\\{d\over dx}f'(t)dt=f'(x^2)\times2x}$$
## Chain Rule Version
If u and v are functions of x, then$${d\over dx}\int_u^vf(t)\,dt=f(v)v'-f(u)u'$$This way, you don't need to integrate!
### Worked Example
$$\displaylines{{d\over dx}\int_{-1}^{x^3}(t^2+2t)\,dt\\=((x^3)^2+2x^3)3x^2\\=(x^6+2x^3)3x^2}$$