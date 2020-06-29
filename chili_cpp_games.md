# Chili C++ Games

## MineSweeper

- [x] MineField
  - [x] game state
  - [x] tiles
  - [x] update
  - [x] draw
- [x] Tile
  - [x] update
  - [x] draw
- [x] Game
  - [x] check win or lose

## Tips on Exploring A New CodeBase

- for a specific feature, look at the related commit changes
- start from public function signatures

## Six Special Member Functions in A Cpp Class


````cpp
class A
{
public:
    A(); // default constructor
    A(const A&); // copy constructor
    ~A(); // destructor
    A& operator=(const A&); // copy assign operator
    // two more in C++11...
}
````

> **Rule of 3**:
> If you implement any one of the `copy constructor`, `copy assign`, `destructor`, you should _consider_ implementing all 3 of them.
>
> **Rule of 0**:
> Don't implement any one of the `copy constructor`, `copy assign`, `destructor` unless you have a good reason.

## RValues

```cpp
// rvalue s can only appear on right side of assign (=)
// literal int
420 = 69; // error
// temporary return value from function
f() = 420; // error
```
