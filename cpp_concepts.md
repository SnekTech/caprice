# Some Confusing Concepts in C++

## Basic Types and Variables

### `signed char`

If you need a tiny integer, explicitly specify either `signed char` or `unsigned char`.

### `float` vs. `double`

`double` is preferable to `float`, and may not cost too much.

### The Comma Operator - `,`

The comma operator takes two operands, which it evaluates from left to right. The result of a comma expression is the value of its right-hand expression(the left result is discarded). The result is an lvalue if the right-hand result is an lvalue.

### Operator Overloading

基础类型的内置操作符无法被重载，用户重载的操作符至少应涉及一个自定义类型。

自定义类型的成员操作符重载，有一个隐式指针参数`this`，指向当前对象。
