# Geometric



## Introduction

- midpoint on log scale
- value at equal distance between values on log scale
- only for strictly positive values

$$ \bar{x} := \left( \prod_{i=1}^n x_i \right)^{\frac{1}{n}} = \left( x_1 x_2 \cdots x_n \right)^{\frac{1}{n}} $$

- also called log-average
- arithmetic mean of logarithms interpreted as logarithm

$$ \begin{aligned} \bar{x} &= \exp \left( \ln \left( \left( x_1 x_2 \cdots x_n \right)^{\frac{1}{n}} \right) \right) \\
&= \exp \left( \frac{1}{n} \ln \left( x_1 x_2 \cdots x_n \right) \right) \\
&= \exp \left( \frac{1}{n} \left( \ln x_1 + \ln x_2 + \cdots + \ln x_n \right) \right) \end{aligned} $$

- length of side of hypercube with equal volume as hyperrectangle with sides of lengths of values
- average growth rate of growth rates $x_i := \frac{a_i}{a_{i-1}}$ for sequence $a_0, a_1, \ldots, a_n$ and $i \in \{1, \ldots, n\}$

$$ \begin{aligned} \bar{x} &= \left( x_1 x_2 \cdots x_n \right)^{\frac{1}{n}} \\
&= \left( \frac{a_1}{a_0} \frac{a_2}{a_1} \cdots \frac{a_n}{a_{n-1}} \right)^{\frac{1}{n}} \\
&= \left( \frac{a_n}{a_0} \right)^{\frac{1}{n}} \end{aligned} $$

- median in a geometric progression, e.g. 9 in 3, 9, 27
- used when values differ widely
