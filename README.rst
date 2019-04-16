NOTES & MATH DOCUMENTATION
=======

[Documentation]: http://www.reduce-algebra.com/reduce38-docs/reduce.pdf

A list of supported math commands. The math module of Notes & Math is based on Reduce CAS and so a complete list of commands and functions can be found in the Reduce CAS documentation ([Documentation]). Not all functionality of Reduce CAS is supported in notes & math.


Integrals
------------

General notation::

    int(expression, [lower bound], [upper bound], var)

The command 'int' returns the indefinite or definit integral of an expression.

#### Examples:

1) Indefinit integration of the function x^2, with respect to the variable x:

Notes & math command:: 
    
    int(x^2,x)

2) Definit integration of the function x^2 from 3 to 5, with respect to the variable x:

Notes & math command:: 

    int(x^2,x,3,5)


ARCCOS
------------

General notation::

	acos(expression)

The command 'acos' returns the value of the inverse cosine function.

#### Examples:

1) Calculating the acos value of 0.5::

	acos(0.5) = 1.0472


ARCCOSH
------------

General notation::

	acosh(expression)

The command 'acosh' returns the inverse hyperbolic cosine for each element of X.

#### Examples: 

1) Calculating the acosh value when X is 4

	y=acosh(4) = 2.0634


ARCCOTH
------------

General notation::

	acoth(expression)

The command 'acoth' returns the inverse hyperbolic cotangent for each element of X.

#### Examples:

1) Calculating the acoth value when X is 4

	y=acoth(4) = 0.2554


ARCCSC
------------

General notation::

	acsc(expression)

the command 'acsc' 

ARCSIN
------------ 

General notation::
	
	asin(expression)

The command 'asin' returns the value of the inverse sine function.

#### Examples:

1) Calculating the asin value of 0.5::

	acos(0.5) = 0.5236