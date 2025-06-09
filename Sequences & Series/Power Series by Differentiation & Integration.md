#APCalc 
#Math 
[[2025-02-08#More Power Series]]

Power Series: [[Definition of Geometric & Power Series#Power Series]]
# Power Series by Differentiation
$$\displaylines{f(x)={1\over1-x}=1+x+x^2+x^3+\cdots\\f'(x)=0+1+2x+3x^2+\cdots}$$$$\displaylines{j(x)=1+x+{x^2\over2!}+{x^3\over3!}+\cdots\\j'(x)=0+1+{2x\over2!}+{3x^2\over3!}+\cdots\\j'(x)=1+x+{x^2\over2!}+{x^3\over3!}+\cdots\\j(x)=j'(x)\\\therefore j(x)=e^x}$$
# Power Series by Integration
$$\displaylines{\int_0^x{1\over1+t}\,dt=\int_0^x(1-t+t^2-t^3+\cdots+(-1)^nt^n+\cdots)\,dt\\\ln{|1+t|}^x_0=t-{t^2\over2}+{t^3\over3}-{t^4\over4}+\cdots|^x_0\\\ln|1+x|=x-{x^2\over2}+{x^3\over3}-{x^4\over4}+\cdots}$$$$\displaylines{\ln(1+x)=x-{x^2\over2}+{x^3\over3}-{x^4\over4}+\cdots\\\ln(1+(x-1))=x-{x^2\over2}+{x^3\over3}-{x^4\over4}+\cdots\\\ln(x)=(x-1)-{(x-1)^2\over2}+{(x-1)^3\over3}-{(x-1)^4\over4}+\cdots}$$