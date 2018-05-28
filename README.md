# Monoids

A set of objects and operation suct that:

1) The operation is closed over the set.  //(closure)

2) The operation is associative.  //2+(3+5) = (2+3)+5

3) There is identity element. (Ex: for operation addition, 0 is identity as when 0 is added to x, we get x. 1 is identity element for multiplication, 1 is identity element fro divison)


Semi Groups:
Which only has first 2 property, closure, and associative.

All Monoids are semi gropus, but all semi groups are not Monoids.

With mathematic notations:

V = any element   * = operation

E = element of

S = Set

Algebraic struct (S, *) where S = set amd * = operation

Monoids are:
1) Closure      = V(x, y) E S, x*y E S
2) Associative  = V(x, y), z E S, x*(y*s) = (x*y)*s
3) Identity     = V(y) E S, x E S, y*x=y  
