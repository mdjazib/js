Basics:
0-keywords,words
1-variables: var,let,const
2-scope: global,block,functional
3-decalared,assign
4-TDZ: temporal dead zone ( let,const ) ( lines where calling them before initializing )
5-Hoisting ( work on all variables: let,const,var )( meaning: lift )
6-Object.freeze ( for not changing values of object )

Data Types:
0-primitive ( without brackets )
1-referance
2-symbole and bigint data types
3-dynamic typing ( there's no static typing in js which mean we don't define type of variable while declare )
4-typeof quirks ( null type is object, nan type is number ) (behaviour)
5-type coercion ( "5"+1 = "51" )(if operand is a string then it will concatenate while using + but calculate if - )( force )
6-truthy vs falsy ( false values... 0 false "" null undefined NaN document.all )(for checking !! write this before value)(nature)(-1 its truthy)

Operators:
0-types
1-pre/post increment --var / var++
2-unary operator + - ++ -- ! typeof
3-for checking real type of array or object use var instanceof Array / false or true
4-!! we can use before value or variable for checking truthy or falsy

Control Flow:
0-if else else if
1-switch case
2-early return pattern

Loops:
0-for, while, do-while
1-break, continue
2-for-of, forEach, map for arrays
3-for-in, Object entries for objects

Functions:
0-Functions declarations, expressions, and arrow functions ( setting function in variable like let fnc = function(){} is fn expression )
1-parameters vs arguments ( sending values in function is arguments )
2-default, rest and spread parameters
3-return values and early returns
4-first class functions (assign to variables, pass as arguments, return from other functions )
5-higher order functions ( returning a function or receiving a function in params )
6-pure vs impure functions ( if function effect the outside variable is called impure )
7-closures ( a function who return a function while a hof use the variable of its parent function ) and lexical scoping ( function inside function can access the variable of parent function only its function scope from parent to child )
8-IIFE ( immediately invoked function expression )
9-hoisting difference between declaration and expression

Arrays:
0-create,access,modify
1-array methods push,pop,shift,unshift,splice,slice,reverse,sort
2-forEach,map,filter,reduce,find,some,every
3-destructuring, spread operator

Objects:
0-key-value structure
1-dot vs bracket notation
2-nesting and deep access
3-object destructuring
4-loop, for-in, object.keys, object.values, object.entries
5-copying, spread, object.assign, deep clone
6-optional chaining, computed properties
