# Some Confusing Concepts in C++

## Basic Types and Variables

If you need a tiny integer, explicitly specify either `signed char` or `unsigned char`.

`double` is preferable to `float`, and may not cost too much.

Every literal has a type. The form and value of a literal determine its type.

The comma operator takes two operands, which it evaluates from left to right. The result of a comma expression is the value of its right-hand expression(the left result is discarded). The result is an lvalue if the right-hand result is an lvalue.
