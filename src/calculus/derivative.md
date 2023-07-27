# Derivative




integrates derivative or differentiates integral
goes back and forth between integral and derivative
two sides of coin
can't have one without the other

?? chicken and egg problem, can't really define one without the other

## Derivative

- opposite of integral

approximate as rectangle
whatever approaches as dx gets small
approximation gets better an better, less wrong

$$ \mathrm{d}A(x) \approx f(x) \cdot \mathrm{d}x $$

becomes condition, property that mystery function must have, relationship

$$ \frac{\mathrm{d}A(x)}{\mathrm{d}x} \overset{!}{=} f(x) $$

note: dx is never zero, just smaller and smaller

derivative of A is ratio dA/dx as dx gets smaller and smaller

how sensitive a function is to its inputs

- "instantaneous rate of change" makes no sense, oxymoron, instant can't change, needs span of time

velocity is distance per unit time
doesn't make sense at single point in time, needs at least two separate points in time
how can associate individual points in time with function value??? apparent paradox

rise over run slope

consider das/dt as function of t

computer computes it like that

derivative is whatever dS/dt ratio approaches as dt gets smaller and smaller

approaches slope of tangent of graph at point

note: dt is never zero, "infinitely small", always non-zero, just approaches zero

instantaneous change makes not sense, but approaches instant
like flirting with change in instant without ever actually touching it

- slope of tangent line at single point on graph

- best constant approximation for rate of change around a point

derivative := dS/dt as dt approaches zero
-> needs integral S, derivative without integral is like coin with only one side, impossible
beware: not actually a fraction

weirdly, derivative is crazy complicated idea, tiny fractions that each are a mess, get smaller and smaller, what it approaches
and out comes something nice, simple

limit is easier to compute than progressively smaller fractions


## Integral

- opposite of derivative

- weirdly, limit is easier to compute than progressively larger sums

chop up area into rectangles with equal width that approximate it
add up rectangles

area under graph
Full with rectangles

approximates area with rectangles
adds up

\int v(t) \cdot dt
dt also implicitly indicates spacing between timestamps, increases number of rectangles added up as it gets smaller
not a specific sum, whatever sum approaches as dt approaches zero

huge sum, complicated
but approaches something nice

approximating sliver as area
dS \approx v(t) \cdot dt
derivative of area under graph of function is equal to function for graph itself

infinitely many anti-derivatives for constant
shifting graph up or down doesn't change tangent
can determine constant using lower bound of integral

integral of function is anti-derivative of function evaluated at top bound minus bottom bound
constant of anti-derivative doesn't matter as it cancels out
can use any anti-derivative, typically chooses zero as constant
"fundamental theorem of calculus"

this huge sum over many rectangles approaches in limit simple subtraction of two values

think of area as function with variable upper bound
can deduce derivative of area must equal height of graph at each point

can have negative area, area below the curve counts negative
distance traveled backwards
integrals measure signed area between graph and horizontal axis

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