---
layout: post
title: What is a complex vector space?
tags: quantum phyisics
---

A common misconception about physics is that it tries to answer all the
question in the universe when in fact it merely builds mathematical models that
are in line with current observations in hope that it will hold for future
experiments. When it's clear that a model doesn't hold anymore, it needs to be
updated. Some oposition to change is expected; for example the books written by Galileo
Galilei in which he suggested that earth rotates around the sun were banned.
Here, we try to describe some mathematical intruments needed to describe
quantum mechanics.

A vector space (also called a linear space) is a collection of objects called
vectors, which may be added together and multiplied ("scaled") by numbers,
called scalars in this context. Scalars are often taken to be real numbers, 
but there are also vector spaces with scalar multiplication
by complex numbers, rational numbers, or generally any field. The
operations of vector addition and scalar multiplication must satisfy
certain requirements, called axioms.

Here are the axioms a vector space:

(1) Associativity of addition: $$ u + (v + w) = (u + v) + w $$

(2) Commutativity of addition: $$ u + v = v + u $$

(3) Identity of addition: $$ \exists 0 \in V : v + 0 = v \ \forall v \in V $$

(4) Inverse of addition: $$ \forall v \in V \ \exists \ {-}v \in V : v + (-v) = 0 $$

(5) Compatibility of multiplication: $$ a(bv) = (ab)v $$

(6) Identity of multiplication: $$ \exists 1 \in V : 1v = v \ \forall v \in V $$

(7) Distributy of scalar mul in respect to vector addition: $$ a(u + v) = au + av $$

(8) Distributy of scalar mul in respect to field addition: $$ (a + b)v = av + bv $$

Please note that the "+" symbol in equation (7) means vector addition inside V 
while in equation (8) means field addition (e.g. Real numbers addition)

While those axioms mai seem obvious, we encourage the reader to prove that 
$$ R^2 $$ is a vector space in respect with the adding and multiplication 
defined below.

$$ \begin{bmatrix} x_{1} \\ x_{2} \\ \end{bmatrix} + 
   \begin{bmatrix} y_{1} \\ y_{2} \\ \end{bmatrix} =
   \begin{bmatrix} x_{1} + y_{1} \\ x_{2} + y_{2} \\ \end{bmatrix}
$$

and

$$ r \begin{bmatrix} x_{1} \\ x_{2} \\ \end{bmatrix} =
   \begin{bmatrix} rx_{1} \\ rx_{2} \\ \end{bmatrix}
$$
