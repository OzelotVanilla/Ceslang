<h1>The structure of Cesno</h1>

<h2 id="toc">TOC</h2>

- [Variable](#variable)
  - [Properties](#properties)
  - [Rule of naming](#rule-of-naming)
  - [Convention of naming](#convention-of-naming)
- [Value](#value)
  - [Type](#type)
  - [Assign](#assign)
- [Operator](#operator)

Variable
=======================================

Properties
----------

* Strongly typed, statically typed
* Dynamicly typed acceptable, based on staticly typed
* Can set scope ()
* Can be `const` (once init, cannot change)

Rule of naming
---------------

* Legal symbols: A-Z, a-z, 0-9, underscore
* Prohibited starting symbols: 0-9

Convention of naming
--------------------

* Use lower case
* Use underscore to split words

Value
=======================================

Type
----

Already defined (**e** for extendable):

* primitive type: `bit`, `byte`
* numbers: `int`, `deci`, `alge`
  * `int` (**e**): 
  * 
* letters: `char`, `string`
* code object: `func`,`seg`

Assign
------

* type with name: init entity with null value.
  For primitives, just extern.
* type, name, value: init and assign


Operator
=======================================

* Able to create operator because it is a code object