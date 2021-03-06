
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

1) Calculating the acos(x) value when x=0.5::

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

1) Calculating the acoth(x) value when x=4::

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

the command 'asec'  returns the inverse secant of the elements of x in radians.

#### Examples:

1) Calculating the asec(x) value when x=4::


ARCSECH
------------

General notation::

	asech(expression)

the command 'asech' returns the inverse hyperbolic secant for each element of x.

#### Examples:

1) Calculating the asech(x) value when x=4::



ARCSIN
------------ 

General notation::
	
	asin(expression)

The command 'asin' returns the value of the inverse sine function.

#### Examples:

1) Calculating the asin(x) when x=0.5::

	acos(0.5) = 0.5236


ARCSINH
------------

General notation::

	asinh(expression)

The command 'asinh' returns the inverse hyperbolic sine for each element of x.

#### Examples:

1) Calculating the asinh(x) value when x=4::
	
	asinh(4) = 2.0947


ARCTAN
------------

General notation::

	atan(expresssion)

The command 'atan' returns the inverse tangent of the elements of x in radians.

#### Examples:

1) Calculating the inverse tangent value of atan x when x=0.5::
	
	atan(0.5) = 0.4636

2) Find the inverse tangent of the elements of vector x when x=4::
	
	atan(4) = 1.3258


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

	atan2(expression1, expression2)

The command 'atan2'  returns the four-quadrant inverse tangent of Y and X, which must be real. The atan2 function follows the convention that atan2(x,x) returns 0 when x is mathematically zero.

#### Examples:

1)


COS
------------

General notation::

	cos(expression)

The command 'cos' returns the cosine for each element of x.

#### Examples:

1) Calculating the con(x) value when x=4::
	
	cos(4) = -0.6536


COSH
------------

General notation::

	cosh(exprssion)

The command 'cosh' returns the hyperbolic cosine of the elements of x.

#### Examples:

1) Calculating the cosh(x) value when x=4::
	
	cosh(4) = 27.3082


COT
------------

General notation::

	cot(expression)

The command 'cot' returns the cotangent of elements of x.

#### Examples:

1) Calculating the cot(x) value when x=4::

	cot(4) = 0.8637


COTH
------------

General notation::

	coth(expression)

The command 'coth' returns the hyperbolic tangent of the elements of x.

#### Examples:

1) Calculating the coth(x) value when x=4::

	coth(4) = 1.0007


CSC
------------

General notation:

	csc(expression)

The command 'csc' returns the cosecant of the elements of x.

#### Examples:

1) Calculating the csc(x) value when x=4::

	csc(4) = -1.3213


CSCH
------------

General notation:

	csch(expression)

The command 'csch' returns the hyperbolic cosecant of the elements of x.

#### Examples:

1) Calculating the csch(X) value when x=4::

	csch(4) = 0.0366


DILOG
------------

General notation:

	dilog(expression)

The command 'dilog' returns the dilogarithm function.

#### Examples:

1) Calculating dilog(x) value when x=4::

	dilog(4) = -1.939


EI
------------

General notation:

	ei(expression)

The command 'ei' returns the one-argument exponential integral.

#### Examples:

1) Calculating ei(x) value when x=4::

	ei(4) = 19.6309


EXP
------------

General notation:

	exp(expression)

The command 'exp' returns the exponential e^x for each element in array x.

#### Examples:

1) Calculating the exp(x) value when x=4::

	exp(4) = 54.5982


HYPOT
------------

General notation:

	hypot(expression)

The command 'hypot' return the value of a right triangle with side lengths (a,b).

#### Examples:

1) Calculating the hypot(a,b) value when (a,b)=(3,4)::
	
	hypot(3,4) = 5


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


LOG
------------

General notation:

	log(expression)

The command 'log' returns the natural logarithm of each element in array x.

#### Examples:

1) Calculating the log(x) value when x=4::

	log(4) = 1.3863


LOG10
------------

General notation:

	log10(expression)

The command 'log10' returns the common logarithm of each element in array x.

#### Examples:

1) Calculating the log10(x) value when x=4::

	log10(4) = 0.6021


SEC
------------

General notation:

	sec(expression)

The command 'sec' returns the secant of the elements of x.

#### Examples:

1) Calculating the sec(x) value when x=4::

	sec(4) = -1.5299


SECH
------------

General notation:

	sech(expression)

The command 'sech' returns the hyperbolic secant of the elements of x.

#### Examples:

1) Calculating the sech(x) value when x=4::

	sech(4) = 0.0366


SIN
------------

General notation:

	sin(expression)

The command 'sin' returns the sine of the elements of x.

#### Examples:

1) Calculating the sin(x) value when x=4::

	sin(4) = -0.7568


SINH
------------

General notation:

	sinh(expression)

The command 'sinh' returns the hyperbolic sine of the elements of x.

#### Examples:

1) Calculating the sinh(x) value when x=4::

	sinh(4) = 27.2899


SQRT
------------

General notation:

	sqrt(expression)

The command 'sqrt' returns the square root of each element of the array x.

#### Examples:

1) Calculating the sqrt(x) value when x=4::

	sqrt(4) = 2


TAN
------------

General notation:

	tan(expression)

The command 'tan' returns the tangent of each element of x.

#### Examples:

1) Calculating the tan(x) value when x=4::

	tan(4) = 1.1578


TANH
------------

General notation:

	tanh(expression)

The command 'tanh' returns the hyperbolic tangent of the elements of x.

#### Examples:

1) Calculating the tanh(x) value when x=4::

	tanh(4) = 0.9993


FACTORIAL
------------

General notation:

	factorial(expression)

The command 'factorial' returns the product of all positive integers less than or equal to n, where n is a nonnegative integer value.

#### Examples:

1) Calculating the factorial(n) value when n=4

	factorial(4) = 24


FIX
------------

General notation:

	fix(expression)

The command 'fix' rounds each element of x to the nearest integer toward zero.

#### Examples:

1) Calculating the fix(x) value when x is 4,465::

	fix(4,465) = 4


FLOOR
------------

General notation:

	floor(expression)

The command 'floor(x)' rounds each element of X to the nearest integer less than or equal to that element.
The command 'floor(t)' rounds each element of the duration array t to the nearest number of seconds less than or equal to that element.
The command 'floor(t,unit)' rounds each element of t to the nearest number of the specified unit of time less than or equal to that element.


ABS
------------

General notation:

	abs(expression)

The command 'abs' returns the absolute value of each element in array x.

#### Examples:

1) Calculating the abs(x) value when x=-4
	abs(-4) = 4


NEXTPRIME
------------

General notation:

	nextprime(expression)

The command 'nextprime' returns the next prime number greater than or equal to n.

#### Examples:

1) Calculating the nextprime(n) when n=4
	nextprime(4) = 5


ROUND
------------

General notation:
	round(expression)

The command 'round' rounds each element of x to the nearest integer.

#### Examples:

1) Calculating the round(x) value when x=4,657
	round(4,657) = 5