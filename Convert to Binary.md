```js
/*
Description:
Task Overview

Given a non-negative integer n, write a function to_binary/ToBinary which returns that number in a binary format.
Documentation:
Kata.ToBinary Method (Int32)

Returns the binary representation of a non-negative integer as an integer.

Syntax
public static int ToBinary(
int n
  )

Parameters
n
Type: System.Int32
The integer to convert.

Return Value
Type: System.Int32
The binary representation of the argument as an integer.

to_binary(1)  / should return 1 /
to_binary(5)  / should return 101 /
to_binary(11) / should return 1011 /
*/

function toBinary(n){
  return +n.toString(2);
}
```