---
tags:
  - derivatives
---
# Table Of Contents
```table-of-contents
```
The derivative is using the [[Difference Quotient]] to create a prime function.
# $f'(x)$
(f prime of x)
### Existence Of Derivatives
- If the point has a discontinuity, the derivative will not exist
- if the point is continuous, there are a few cases which will not have derivatives
1. Cusp
![[Derivative-20240214132001847.webp|205]]
2. Vertical Tangent. If you drew the tangent, it would be entirely vertical
![[Derivative-20240214132038442.webp|235]]
3. Discontinuity. You cannot have derivatives at discontinuities
![[Derivative-20240214132102215.webp|243]]
4. Absolute function point. Consult [[Absolute Function]]
![[Derivative-20240222201620604.webp|232]]
##### Algebraically
If $f'(x^+)$ DIFFERS WILDLY from $f'(x^-)$, then there is no derivative.
For example, for the absolute function $f(x)=|x|$
$f'(0^-)=-1$
$f'(0^+)=1$
-1 $\neq$ 1

# Notations
### Leibniz Notation
$\frac{dy}{dx}f(x)$
$\lim_{x \to 0} \frac{\triangle y}{\triangle x}f(x)$
### Prime
$f'(x)$

# Derivation Rules
### Derivative Is [[Difference Quotient]]
$$f'(x) = \lim_{ h \to 0 } \frac{f(x+h)-f(x)}{h} $$
### Derivative Of A Constant
$$f(x) = k$$
$$f'(x)=0$$
### Derivative Power Rule
$$f(x) = x^{n}$$
$$f'(x)=nx^{n-1}$$
### Derivative Constant Multiple Rule
[[Derivative Constant Multiple Proof]]
If f(x) is a multiple of another function.
Then the derivative of x, is just the multiple of the derivative of the function.
$$f(x)=kg(x)$$
$$f'(x)=kg'(x)$$
### Derivative Sum/Difference Rule
[[Derivative Sum Difference Proof]]
Derivative of a function is the sum of all derivative components
$$f(x) = p(x) + q(x)$$
$$f'(x) = p'(x) + q'(x)$$
### Derivative Product Rule
[[Derivative Product Rule Proof]]
$$f(x) = p(x) * q(x)$$
$$f'(x) = p'(x) * q(x) + q'(x)*p(x)$$
##### Triple Product Rule
$$f(x) = p(x) * q(x) * r(x)$$
$$f'(x) = p'(x)q(x)r(x) + p(x)q'(x)r(x)+p(x)q(x)r'(x)$$
##### Quadruple Product Rule
$$f(x) = p(x) * q(x) * r(x) * s(x)$$
$$f'(x) = p'(x)q(x)r(x)s(x) + p(x)q'(x)r(x)s(x)+p(x)q(x)r'(x)s(x)+p(x)q(x)r(x)s'(x)$$
### Derivative Chain Rule
[[Derivative Chain Rule Proof]]
For composite functions
$$h(x) = f(g(x))$$
$$h'(x) = g'(x) * f'(x)$$
##### Derivative Power Of A Function Rule
Just the chain rule but for a specific application.
$$h(x)=f(x)^n$$
$$h'(x)=nf(x)^{n-1}*f'(x)$$
