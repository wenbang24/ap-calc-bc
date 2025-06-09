#APCalc 
#Math 
# Definition
- One or both limits of integration is infinity or negative infinity
- Vertical asymptote **at or between** limits
# Solving
## For improper integrals with improper limits
$$\int_n^\infty f(x)\,dx=\lim_{b\rightarrow\infty}\int_n^bf(x)\,dx$$
## For improper integrals with vertical asymptotes
$$\displaylines{\int_a^bf(x)\,dx=\int_a^mf(x)\,dx+\int_m^bf(x)\,dx\\=\lim_{n\rightarrow m}\int_a^nf(x)\,dx+\lim_{n\rightarrow m}\int_n^bf(x)\,dx}$$
### Worked example:
$$\displaylines{\int_{-1}^2\frac{1}{x^3}\,dx\\=\int_{-1}^0\frac{1}{x^3}\,dx+\int_0^2\frac{1}{x^3}\,dx\\=\lim_{b\rightarrow0^-}[-{1\over2x^2}]^b_{-1}+\lim_{b\rightarrow0^+}[-{1\over2x^2}]^2_b\\=\infty+{1\over2}-{1\over8}+\infty\\=\infty}$$