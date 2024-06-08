---
date: 2024-06-08
category:
  - topic
---
# Definition of integral
This is using the Riemann Sums
$$\lim_{n\rightarrow \infty}\sum^n_{k=1}(\frac{b-a}{n}\cdot f (a+\frac{b-a}n k) = \int ^b _a f(x) dx $$
# Theorem of Calculus
[[Integral]] is the inverse of [[Derivatives]]
$$ \frac{d}{dx} \int^x_a f(t) dt = f(x)$$
$$ \frac{d}{dx} \int^{g(x)}_a f(t) dt = f(g(x)) \cdot g'(x)$$
$$ \frac{d}{dx} \int^{g(x)}_{h(x)} f(t) dt = f(g(x)) \cdot g'(x) - f(h(x)) \cdot h'(x)$$
# Equivalent limits
$$\int^a_a f(x) dx = 0$$
# Reversal of limits
$$\int^a_b f(x) dx = - \int^b _a f(x) dx$$
#  Multiply by constant
$k$ is a constant
$$\int^a_b kf(x) dx = k \int^a_b f(x) dx$$
# Adjacent Intervals
$a<c<b$
$$\int^c_a f(x) dx +\int ^b_cf(x) dx = \int^b_af(x)dx $$
# Addition
$$\int^a_b [f(x)+g(x)] dx = \int^a_b f(x)dx + \int^a_b g(x)dx$$
# Subtraction
$$\int^a_b [f(x)-g(x)] dx = \int^a_b f(x)dx - \int^a_b g(x)dx$$
# Power rule
$$\int x^n dx = \frac{x^{n+1}}{n+1} + c$$
# Exponential
$$\int e^x dx = e^x +c$$
$$\int a^x dx = \frac{1}{\ln (a)}a^x +c$$
# Special case
$$\int \frac{1}x dx = \ln(|x|) +c$$
