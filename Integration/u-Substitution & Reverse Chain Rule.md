#Math 
#APCalc
[[2024-11-17]]
# Steps
If you can't integrate something, try and make another variable u in terms of x so you can substitute it in and integrate (don't forget to substitute dx for du).
# Worked Examples
$$
\displaylines{\int(3x-1)^{10}\,dx\\\text{Let }u=3x-1\\{du\over dx}=3\rightarrow{1\over3}du=dx\\\text{Now substitiute $3x-1$ for u and dx for ${1\over3}du$:}\\\int u^{10}{1\over3}du={1\over3}\int u^{10}\,du\\={1\over3}{u^{10+1}\over10+1}\\={u^{11}\over33}+C\\={(3x-1)^{11}\over33}+C}
$$
$$
\displaylines{\int (3t^2+2t)(t^3+t^2)\,dt\\u=t^3+t^2,{du\over dt}=3t^2+2t\rightarrow du=(3t^2+2t)dt\\=\int u\,du\\={u^2\over2}+C\\={(t^3+t^2)^2\over2}+C}
$$