#Math 
#APCalc 
[[2025-03-01]]
In the form $(r, \theta)$.
The line $\theta = 0$ is called the pole.
$\theta$ goes anti-clockwise from the positive x-axis on the cartesian plane.
$\theta = 0 \equiv 2\pi$
# Conversion
$$\displaylines{x^2+y^2=r^2\\\tan\theta={y\over x}\\x=r\cos\theta\\y=r\sin\theta}$$
[[2025-03-09]]
# Polar graphs
## Rose petal curves
$$r=k\sin(x\theta),\,k\cos(x\theta)$$If x is even, number of petals is 2x
If x is odd, number of petals is x
Distance from origin to end of petal is k
## Limaçons
$$\displaylines{r=a\pm b\cos\theta\,\text{(x axis symmetry)}\\r=a\pm b\sin\theta\,\text{(y axis symmetry)}}$$If b > a, there are inner loops
# Derivatives
Plug in your equation for r into $x=r\cos\theta$ or $y=r\sin\theta$, then find $dx\over d\theta$ and $dy\over d\theta$ (treat it like a [[Parametric Equations]], ${dy\over dx}={dy/d\theta\over dx/d\theta}$). Remember [[Polar Graphs#Conversion]].
Don't forget ${y\over x}=\tan\theta$ to find theta at a point, since dy/dx will be in terms of theta.
# Horizontal & Vertical Tangents
Ignore $r=0$ and $\theta=0$.
Horizontal:$${dy\over dx}=0\rightarrow {dy\over d\theta}=0$$Vertical: $${dy\over dx}=\infty\rightarrow {dx\over d\theta}=0$$
# Polar Area/Polar Integration
$${1\over2}\int_\alpha^\beta r^2d\theta$$where $\alpha$ is your starting angle, and $\beta$ is your ending angle.
Solve for the bounds, don't just look and assume.
# Point(s) of intersection
Set r equal, solve for theta
# Area between two curves
1. Find [[#Point(s) of intersection]]
2. Find which is closer to the radius between the points of intersection, and integrate accordingly
## Example 1
Find the area common to $r=-6\cos\theta$ and $r=2-2\cos\theta$.
$$\displaylines{-6\cos\theta=2-2\cos\theta\\\cos\theta=-1/2\\\theta=2\pi/3,4\pi/3\\\text{Area}=2\times\left({1\over2}\int_{\pi\over2}^{2\pi/3}(-6\cos\theta)^2\,d\theta+{1\over2}\int_{2\pi/3}^\pi(2-2\cos\theta)^2\,d\theta\right)}$$
## Example 2
Find the area between the loops of $r=2(1+2\sin\theta)$ (this is a limaçon with a loop).
Finding points where $r=0$:$$\displaylines{0=2(1+2\sin\theta)\\\sin\theta=-1/2\\\theta=7\pi/6,11\pi/6}$$Area of whole left half:$${1\over2}\int_{\pi/2}^{7\pi/6}r^2\,d\theta$$Area of right half of inner loop:$${1\over2}\int_{7\pi/6}^{3\pi/2}r^2\,d\theta$$Area in between:$$2\times\left({1\over2}\int_{\pi/2}^{7\pi/6}(2(1+2\sin\theta))^2\,d\theta-{1\over2}\int_{7\pi/6}^{3\pi/2}(2(1+2\sin\theta))^2\,d\theta\right)$$
# Polar Arc Length
$$\int_\alpha^\beta\sqrt{r^2+\left({dr\over d\theta}\right)^2}\,d\theta$$
