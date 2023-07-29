# Derivative



## Introduction

- integral and derivative are opposites, two sides of same coin
- can't have one without the other, can't have coin with only one side
- integrates a derivative, differentiates an integral
- goes back and forth between integral and derivative, like turning a coin, taking steps on infinite ladder
- same, integral is also derivative, derivative is also integral, depends on point of view, like which sides of coin looks at
- chicken and egg problem, can't define one without the other, can define only together

- looks at limit, what happens when $\Delta x$ goes to zero
- $\mathrm{d}x$ never is zero, only approaches zero
- beware: "infinitely small" is misleading!
- path towards limit is complex, tiny fractions or products
- limit is nice and simple, magic
- limit is easier to compute than path towards it
- computer computes it numerically with finite fractions or products



## Motivation

- wants to relate graph and area under graph
- approximate area with rectangles
- rectangle is

$$ \Delta A(x) \approx f(x) \cdot \Delta x $$

- can get graph function by dividing rectangle by width
- tiny fraction
- graph function called derivative of area function
- slope of tangent on graph of area function at point

$$ f(x) \approx \frac{\Delta A(x)}{\Delta x} $$

- can get area by summing up all rectangles
- huge sum of tiny products
- area function called integral of graph function
- $\Delta x$ implicitly indicates number of rectangles, increase as it gets smaller

$$ A = \sum \Delta A(x) \approx \sum f(x) \cdot \Delta x $$

whatever approaches as Dx gets smaller and smaller
approximation gets better an better, less wrong
becomes condition, property that mystery function must have, relationship
- in limit when $\Delta x$ goes to zero writes

$$ \mathrm{d}A(x) = f(x) \cdot \mathrm{d}x $$



## Derivative

- ratio

$$ \frac{\mathrm{d}f(x)}{\mathrm{d}x} $$

- beware: not actual fraction,  not any specific fraction, whatever fractions approach as goes to zero!
- think of fraction as single symbol, not actual division, only reminiscent of origin
- think of fraction as operator

$$ \frac{\mathrm{d}}{\mathrm{d}x} f(x) $$

- appearance of division is suggestive of properties of operator, e.g. multiple derivatives, chain rule, inversion, etc.

- slope of tangent on graph at point
- measure of how sensitive function is to its input
- best constant approximation for rate of change around a point
- not "instantaneous rate of change", oxymoron, can't have change in an instant, makes no sense
- only as approaches instant, over smaller times, like flirting with change in instant without ever actually touching it
- but limit exists, can associate instant with change, apparent paradox



## Integral

- sum

$$ \int f(x) \cdot \mathrm{d}x $$

- beware: not actual sum, not any specific sum, whatever sums approach as goes to zero!
- appearance of sum is suggestive of properties of operator, e.g. multiple integrals, chain rule, etc.

- signed area under graph between two points
- area below axis counts negative, inverse function, e.g. distance traveled backwards

- anti-derivative is signed area with variable upper bound
- infinitely many anti-derivatives for function by added constant, shifts graph of function up or down, tangent line stays same
- integral is anti-derivative at upper bound minus anti-derivative at lower bound, constant doesn't matter as it cancels out, can use any anti-derivative, typically chooses constant zero, "fundamental theorem of calculus"
- huge complicated sum over smaller rectangles approaches in limit simple subtraction of two values, apparent paradox



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

- [3Blue1Brown - Essence of calculus](https://youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr)
