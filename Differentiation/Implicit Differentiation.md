#Math 
#APCalc 
[[2024-10-19#AP Calc]]
1. Differentiate both sides with respect to x
	1. Differentiate any terms with y
	2. Multiply by $y'$ chain rule factor for any term with y
		1. y is $g(x)$ here: [[02 - Academic Things/Math/Archive/AP Calculus BC/Differentiation/Basic Rules#Chain Rule]]
2. Collect all $y'$ terms on one side
3. Factor out $y'$
4. Solve for $y'$
# Worked Examples
$$\displaylines{x^3-2xy+y^3=5x\\{d\over dx}(x^3-2xy+y^3)={d\over dx}(5x)\\3x^2-2xy'-2y+3y^2y'=5\text{ (use product rule for -2xy term where }u=-2x\text{ and }v=y ,v'=y')\\-2xy'+3y^2y'=5+2y-3x^2\\y'=\frac{5+2y-3x^2}{3y^2-2x}}$$
## Worked example for second derivative
For $y''$ and so on, first solve for $y'$, take the derivative of that again and then substitute in any $y'$s:$$\displaylines{x^2+y^2=3\\{d\over dx}(x^2+y^2)={d\over dx}(3)\\2x+2yy'=0\\y'={-x\over y}\\y''=\frac{-y+xy'}{y^2}\text{ (quotient rule)}\\y''=\frac{-y+{-x^2\over y}}{y^2}\\y''=\frac{-y^2-x^2}{y^3}\\y''={-3\over y^3}}$$