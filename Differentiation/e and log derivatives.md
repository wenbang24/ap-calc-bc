#APCalc 
#Math
[[2024-10-12#AP Calc]]
$$
{d\over dx}e^{f(x)}=f'(x)e^{f(x)}
$$$$
{d\over dx}\ln f(x) = {f'(x)\over f(x)}
$$
# Other Bases
## a^x
$$
\displaylines{{d\over dx}a^x=a^x\ln a\\{d\over dx}a^{f(x)}=a^{f(x)}\times\ln a\times f'(x)}
$$
### Proof
$$
\displaylines{e^{\ln a^x}=a^x\\ {d\over dx}a^x\\={d\over dx}e^{\ln a^x}\\={d\over dx}e^{x\ln a}\\=e^{x\ln a}\ln a\\=a^x\ln a}
$$
## loga(x)
$$
\displaylines{{d\over dx}\log_ax={1\over x\ln a}\\{d\over dx}\log_af(x)=\frac{f'(x)}{f(x)\ln a}}
$$
### Proof
$$
\displaylines{{d\over dx}\log_ax\\={d\over dx}\frac{\ln x}{\ln a}\\=\frac{1}{\ln a}\times{d\over dx}\ln x\\=\frac{1}{x\ln a}}
$$
# Logarithmic Differentiation
1. take ln (or another log but ln is recommended) of both sides
2. simplify right side
3. differentiate (yes ${d\over dx}\ln y$ becomes ${y'\over y}$ not $1/y$)
4. solve for y'
5. substitute in y (if necessary)