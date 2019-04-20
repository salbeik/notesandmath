
<script src="https://fred-wang.github.io/mathjax.js/mpadded-min.js"></script>

NOTES & MATH DOCUMENTATION
======= 

[Documentation]: http://www.reduce-algebra.com/reduce38-docs/reduce.pdf

A list of supported math commands. The math module of Notes & Math is based on Reduce CAS and so a complete list of commands and functions can be found in the Reduce CAS documentation ([Documentation]). Not all functionality of Reduce CAS is supported in notes & math.





ACOS
------------

General notation::

	acos(expression)

The command 'acos' returns the value of the inverse cosine function <html> <math>
  <msup> 
   <mi>cos</mi> 
      <mn>-1</mn>
   </msup>
   <mi>(x)</mi> 
</math>
</html>

#### Examples:

1) Calculating the acos value of 0.5::

	acos(0.5) = 1.0472


ACOSH
------------

General notation::

	acosh(expression)

The command 'acosh(x)' returns the inverse hyperbolic cosine for each element of the expression x.

#### Examples: 

1) Calculating the acosh(x) value when x=4::

	acosh(4) = 2.0634


ACOTH
------------

General notation::

	acoth(expression)

The command 'acoth' returns the inverse hyperbolic cotangent for each element of the expression.

#### Examples:

1) Calculating the acoth value when x=4::

	acoth(4) = 0.2554


ARCCSC
------------

General notation::

	acsc(expression)

the command 'acsc' 


ARCCSCH
------------

General notation::

	acsch(expression)

the command 'acsch'


ARCSEC
------------

General notation::

	asec(expression)

the command 'asec'  returns the inverse secant of the elements of X in radians.

#### Examples:

1) Calculating


ARCSECH
------------

General notation::

	asech(expression)

the command 'asech' returns the inverse hyperbolic secant for each element of x.

#### Examples:

1) Calculating the asech value when X is 4::



ARCSIN
------------ 

General notation::
	
	asin(expression)

The command 'asin' returns the value of the inverse sine function.

#### Examples:

1) Calculating the asin value of 0.5::

	acos(0.5) = 0.5236


ARCSINH
------------

General notation::

	asinh(expression)

The command 'asinh' returns the inverse hyperbolic sine for each element of x.

#### Examples:

1) Calculating the asinh value when X is 4::
	Y = asinh(4) = 2.0947


ARCTAN
------------

General notation::

	atan(expresssion)

The command 'atan' returns the inverse tangent of the elements of x in radians.

#### Examples:

1) Calculating the inverse tangent value when atan is 0.5::
	atan(0.5) = 0.4636
2) Find the inverse tangent of the elements of vector X when X is 4::
	y=atan(4) = 1.3258


ARCTANH
------------

General notation::

	atanh(expression)

The command 'atanh' returns the inverse hyperbolic tangent for each element of x.

#### Examples:

1) Calculating the atanh value


ARCTAN2
------------

General notation::

	atan2(expression)

The command 'atan2'  returns the four-quadrant inverse tangent of Y and X, which must be real. The atan2 function follows the convention that atan2(x,x) returns 0 when x is mathematically zero.

#### Examples:

1)


COS
------------

General notation::

	cos(expression)

The command 'cos' returns the cosine for each element of x.

#### Examples:

1) Calculating the con value of 4::
	
	cos(4) = -0.6536


COSH
------------

General notation::

	cosh(exprssion)

The command 'cosh' returns the hyperbolic cosine of the elements of x.

#### Examples:

1) Calculating the cosh value when x is 4::
	
	cosh(4) = 27.3082


COT
------------

General notation::

	cot(expression)

The command 'cot' returns the cotangent of elements of x.

#### Examples:

1) Calculating the cot value 




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