# Derivative




integral and derivative are opposites, two sides of same coin
can't have one without the other, needs to have integral to make derivative, needs to have derivative to make integral, can't have coin with one side
integrates a derivative or differentiates an integral
goes back and forth between integral and derivative
depends on point of view, what wants, always both exists
like steps on an infinite ladder

?? chicken and egg problem, can't really define one without the other

looks at limit, what happens when dx goes to zero
never is zero, approaches
magic falls out, limit is nice and simple, path towards limit is complex
tiny fractions
huge sums of tiny products
limit is easier to compute than path towards it
dt is never zero, "infinitely small", always non-zero, just approaches zero



## Derivative

approximate as rectangle
whatever approaches as dx gets small
approximation gets better an better, less wrong

$$ \mathrm{d}A(x) \approx f(x) \cdot \mathrm{d}x $$

becomes condition, property that mystery function must have, relationship

$$ \frac{\mathrm{d}A(x)}{\mathrm{d}x} \overset{!}{=} f(x) $$

derivative of A is ratio dA/dx as dx gets smaller and smaller
beware: not actually a fraction
whatever ratio approaches as dx gets smaller and smaller
approaches slope of tangent of graph at point
think of fraction as single symbolic symbol reminding of where it came from
think of d/dx as operator
division appearance is suggestive of properties of operator, allows to remember easier
like multiple derivatives, chain rule, inversion, etc.

$$ \Delta $$

- measure of how sensitive a function is to its input

rise over run slope

consider ds/dt as function of t

computer computes it like that

- slope of tangent line on graph at a point
- best constant approximation for rate of change around a point
- beware: "instantaneous rate of change" makes no sense, oxymoron, instant can't change, needs span of time, yet limit does exist
instantaneous change makes not sense, but approaches instant
like flirting with change in instant without ever actually touching it
velocity is distance per unit time
doesn't make sense at single point in time, needs at least two separate points in time
how can associate individual points in time with function value??? apparent paradox

$$ f'(x) := \lim_{\mathrm{d}x \to 0} \frac{f(x)}{\mathrm{d}x}$$



## Integral

chop up area into rectangles with equal width that approximate it
add up rectangles

area under graph
Full with rectangles

approximates area with rectangles
adds up

$$ \int v(t) \cdot \mathrm{d}t $$

dt also implicitly indicates spacing between timestamps, increases number of rectangles added up as it gets smaller
not a specific sum, whatever sum approaches as dt approaches zero

approximating sliver as area
dS \approx v(t) \cdot dt
derivative of area under graph of function is equal to function for graph itself

infinitely many anti-derivatives for constant
shifting graph up or down doesn't change tangent
can determine constant using lower bound of integral

- anti-derivative of function evaluated at top bound minus bottom bound
constant of anti-derivative doesn't matter as it cancels out
can use any anti-derivative, typically chooses zero as constant
"fundamental theorem of calculus"

this huge sum over many rectangles approaches in limit simple subtraction of two values


- measure of signed area between graph and horizontal axis
- area below the curve counts negative, inverse function, e.g. distance traveled backwards


- think of area as function with variable upper bound
- approximate additional unit of area by rectangle

$$ \mathrm{d}A(x) \approx f(x) \cdot \mathrm{d}x $$

- derivative of area must equal height of graph at each point, condition, property, relationship

$$ \frac{\mathrm{d}A(x)}{\mathrm{d}x} \overset{!}{=} f(x) $$

////

average of continuous variable
how to add up all and divide by number
how to divide by infinitely many?

average height is area divided by width
integral divided by interval length

integral is also slope of line through anti-derivative graph at lower and upper bound
average value of function is average slope over all tangent lines between lower and upper bound
average slope between bounds equals total slope between lower and upper bounds




## Resources

- [3blue1brown ...]()