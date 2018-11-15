# Readme

Code snippets to speed up writing of ABAP.

https://marketplace.visualstudio.com/items?itemName=frehu.abap-snippets

Currently included:

Borrowed from other languages:
- bool = abap_bool
- true = abap_true
- false = abap_false
- var = inline data declaration
- nameof = name of current class (file)
- self, this = me->

Types:
- trt = type ref to
- tt, ttt, tst, tht = table type definitions
- tbo = structure type definition (types begin of)
- enum = enum definition
- alias

Methods:
- im, ex, ch, rv = importing, exporting, changing, returning value
- meth = empty method body
- gwt = empty unit test with given/when/then sections
- ctor, cctor = constructor, class-constructor definition

Other:
- ro = read-only
- ii = is initial
- ini = is not initial
- ib = is bound
- inb = is not bound
- inh = inheriting from 
- class = empty class definition + implementation
- if
- trycatch
- loop = loop into data
- loopfs = looping into field symbol
- cond
- for = for expression
- forw = for expression with where condition
- val = value constructor
- case
- ass = cl_abap_unit_assert=>
- throw = raise exception new
