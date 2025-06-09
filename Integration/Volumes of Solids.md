#APCalc 
#Math
[[2025-02-01]]
# Volumes of Solids with Known Cross Sections
## Cross-sections perpendicular to the x-axis:
$$V=\int_a^bA\,dx$$where A is a function of x and gives the cross sectional area
## Cross-sections perpendicular to the y-axis:
$$V=\int_c^dA\,dy$$where A is a function of y and gives the cross sectional area
### Example
**Set up integrals for the volumes of the solids whose base is the circle $x^2+y^2=1$ and whose cross sections are:**
#### Equilateral triangles perpendicular to the y-axis
$$\displaylines{x^2+y^2=1\\x^2=1-y^2\\x=\pm\sqrt{1-y^2}\\\text{Side length of equilateral triangle: }\sqrt{1-y^2}--\sqrt{1-y^2}\\=2\sqrt{1-y^2}\\V=\int_{-1}^1{\sqrt{3}\over4}(2\sqrt{1-y^2})^2\,dy\\V=\int_{-1}^1\sqrt{3}(1-y)^2\,dy}$$
#### Rectangles whose heights are three times their bases perpendicular to the y-axis
$$\displaylines{\text{Base of rectangle: }2\sqrt{1-y^2}\\\text{Height of rectangle: }6\sqrt{1-y^2}\\\text{Area: }(2\sqrt{1-y^2})(6\sqrt{1-y^2})\\=12(1-y^2)\\V=\int_{-1}^112(1-y^2)\,dy}$$
## Circular cross sections (discs)
$$V=\pi\int_a^br^2\,dx$$where r is a function of x that gives the radius
Basically rotating the function about the x axis
Similar integral for y
### Example
**Find the volume of a solid formed by revolving the region in Quadrant I bounded by $y=x^2,x=0$ and $y=4$ about the y-axis**
$$\displaylines{x=\sqrt{y}\\r(y)=\sqrt{y}-0=\sqrt{y}\\V=\pi\int_0^4r(y)^2\,dy\\V=\pi\int_0^4y\,dy\\V=\pi(y^2/2)|^4_0\\V=8\pi}$$
## Washers
When a region is revolved around an axis that is not one of its bounds$$V=\pi\int_a^bR^2-r^2\,dx$$where $R$ and $r$ are functions of x that give the outer and inner radii (distance from the axis of revolution)
Similar integral for y
##### Example 1
**Set up integrals for the volumes of the solids formed by revolving the region bounded by $y=-x^2+x$ and $y=0$**
###### i) about $y=-1$ (below region)
$$\displaylines{R(x)=-x^2+x--1=-x^2+x+1\\r(x)=0--1=1\\V=\pi\int_0^1R(x)^2-r(x)^2\,dx\\V=\pi\int_0^1(-x^2+x+1)^2-1^2\,dx}$$
###### ii) about $y=2$ (above region)
$$\displaylines{R(x)=2-0=2\\r(x)=2-(-x^2+x)=x^2-x+2\\V=\pi\int_0^1R(x)^2-r(x)^2\,dx\\V=\pi\int_0^12^2-(x^2-x+2)^2\,dx}$$
### Example 2
**Set up integrals for the volumes of the solids formed by revolving the region bounded by $y=x^2$ and $y=x+2$**
#### about the x-axis
$$\displaylines{R(x)=x+2-0=x+2\\r(x)=x^2-0=x^2\\V=\pi\int_{-1}^2R(x)^2-r(x)^2\,dx\\V=\pi\int_{-1}^2(x+2)^2-(x^2)^2\,dx}$$
#### about $y=4$
$$\displaylines{R(x)=4-x^2\\r(x)=4-(x+2)=-x+2\\V=\pi\int_{-1}^2R(x)^2-r(x)^2\,dx\\V=\pi\int_{-1}^2(4-x^2)^2-(-x+2)^2\,dx}$$