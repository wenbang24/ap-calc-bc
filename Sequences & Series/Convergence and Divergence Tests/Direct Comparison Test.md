#APCalc 
#Math 
[[2025-02-22#Direct Comparison Test]]
Let $0<a_n\leq b_n$ for all $n$ after a certain $n$. Then, $$
\displaylines{\text{If }\sum_{n=1}^\infty b_n\text{ converges, then }\sum_{n=1}^\infty a_n\text{ also converges}\\\text{If }\sum_{n=1}^\infty b_n\text{ diverges, then }\sum_{n=1}^\infty a_n\text{ also diverges}}
$$If the b-series diverges then the a-series diverges too.
Informally:
- If the 'larger' (b) series converges then the 'smaller' (a) series must also converge
- If the 'larger' (b) series diverges then the 'smaller' (a) series must also diverges
# Example
$$
\displaylines{\text{Does }\sum_{n=1}^\infty{1\over1+2^n}\text{ converge?}\\\text{Compare to }\sum_{n=1}^\infty{1\over2^n}=\sum_{n=1}^\infty({1\over2})^n\\{1\over2}<1,\text{ therefore it converges}\\{1\over2^n}>{1\over1+2^n}\\\text{Therefore, }\sum_{n=1}^\infty{1\over1+2^n}\text{ converges}}
$$