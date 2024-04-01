---
tags:
  - derivatives
aliases:
  - Power Rule
  - Sum Rule
  - Quotient Rule
  - Product Rule
  - Chain Rule
---
# Table Of Contents 
```table-of-contents
```
The derivative is using the [[Difference Quotient]] to create a prime function.
# $f'(x)$
(f prime of x)
### [[Differentiability]]
For a point to be differentiable and have a derivative, it must:
1. Be continuous at that point
2. $$f'(x^-)=f'(x)=f'(x^+)$$left limit's **slope** be the same as the right limit's **slope** which is same as the limit's **slope**. If there is a sharp jump from one slope to the other, then it is not differentiable

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
### Derivative Quotient Rule
$$f(x) = \frac{h(x)}{g(x)}$$
$$f'(x) = \frac{h'(x)g(x) - g'(x)h(x)}{(g(x))^2}$$
### Derivative Chain Rule
[[Derivative Chain Rule Proof]]
For composite functions
$$h(x) = f(g(x))$$
$$h'(x) = g'(x) * f'(x)$$
##### Derivative Power Of A Function Rule
Just the chain rule but for a specific application.
$$h(x)=f(x)^n$$
$$h'(x)=nf(x)^{n-1}*f'(x)$$
### Derivative Exponential with [[Euler's Number]] Base
$$h(x)=e^x$$
$$h'(x) = e^x$$
##### (Chain Rule) Exponential Euler's Number Base
$$g(x)=e^{f(x)}$$
$$g'(x) = e^{f(x)}*f'(x)$$
### Derivative Of A General Exponential Function
$$f(x)=b^x$$
$$f'(x)=b^x*\ln b$$
You just use the natural logarithm
With a function:
$$g(x)=b^{f(x)}$$
$$g'(x)=b^{f(x)}*f'(x)*\ln b$$
### Derivative Of Natural Logarithm
$$f(x)=\ln x$$
$$f'(x)=\frac{1}{x}, \{x>0\}$$
For all values greater than 0
[[Natural Logarithm Derivative Proof]]
##### (Chain Rule) Derivative Of Composite Natural Logarithm
$$f(x) = \ln(g(x))$$
$$f'(x) = \frac{1}{g(x)}g'(x)$$
### Derivative Of General Logarithmic Function
$$f(x)=\log_{a}x\ \ \ \  a>0,a\neq 1$$
$$f'(x)=\frac{1}{x\ln a}$$
### Derivative Of Sine Function
$$f(x)=\sin x$$
$$f'(x)=\cos x$$
### Derivative Of Cosine Function
$$f(x)=\cos x$$
$$f'(x)=-\sin x$$
### Derivative Of Tangent Function
$$f(x)=\tan x$$
$$f'(x) = \sec^2x$$
