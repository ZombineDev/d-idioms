=============
Falsey values
=============

In an `if(expr)` condition, `expr` does not need to have boolean type.

Falsey value in D are:
- the integer 0
- the floating point value +0.0 and -0.0
- the `null` pointer / `null` delegate / `null` class reference
- the boolean `false`
- enum members equal to 0
- slices containing a `null` pointer, ie. when `(slice is null)` returns `true`

The empty string `""` and the empty slice `[]` are truthy.
