---
tags:
  - vectors
---
# $\vec{a} \times \vec{b}$
A binary operation between 2 vectors that only works in 3D
### Utilization
- The cross product of 2 vectors gives you the vector perpendicular to the 2
  ![[Cross Product-20240530130224824.webp|348]]
- The cross product scalar value is also the area of the parallelogram created by the 2 vectors
  ![[Cross Product-20240530130353823.webp|370]]
### Formula
##### Vector
Requires you to find the determinant of a 3x3 matrix
![[Cross Product-20240530132142009.webp]]
$$\vec{a} \times \vec{b} = [(a_2 b_3 – a_3 b_2), (–a_1 b_3 + a_3 b_1), (a_1 b_2 – a_2 b_1)]$$
##### Scalar
$$|\vec{a} \times \vec{b}|=|\vec{a}||\vec{b}|\sin \theta$$
### Criss Cross Method
![[Cross Product-20240603142756658.webp]]
![[Cross Product-20240603142839540.webp]]
### Special cases
Any 2 parallels vectors have a cross product of 0 as the angle between them is 0, and as such, $\sin \theta=0$
$\vec{a} \times \vec{a}=0$
# Properties
### Anti Commutative
$\vec{a}\times\vec{b} \neq \vec{b}\times\vec{a}$
$\vec{a}\times\vec{b} =-\vec{b}\times\vec{a}$
### Not Associative
$(\vec{a}\times\vec{b})\times\vec{c} \neq \vec{a}\times(\vec{b}\times\vec{c})$
### Distributive
$\vec{a} \times(\vec{b}+\vec{c}) = \vec{a}\times \vec{b}+\vec{a}\times \vec{c}$
### Scalar Law Multiplication
$k(\vec{p} \times \vec{q})=k\vec{p}\times k\vec{q}$
