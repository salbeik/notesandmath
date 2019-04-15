NOTES & MATH DOCUMENTATION
=======

A list of supported math commands. Notes & Math is based on Reduce CAS and so a complete list of commands and functions can be found in the Reduce CAS documentation. Not all functionality of reduce is supported in notes & math.

[bower]: http://www.reduce-algebra.com/reduce38-docs/reduce.pdf

[bower]

Integrals
------------

Generel notation::

    int(expression, [lower bound], [upper bound], var)

The command 'int' returns the indefinite or definit integral of an expression.

#### Examples:

1) Indefinit integration of the function x^2, with respect to the variable x:

Notes & math command:: 
    
    int(x^2,x)

2) Definit integration of the function x^2 from 3 to 5, with respect to the variable x:

Notes & math command:: 

    int(x^2,x,3,5)







