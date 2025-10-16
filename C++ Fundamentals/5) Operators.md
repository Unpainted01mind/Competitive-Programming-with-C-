# C++ Operators :-

### *Operators are certain mathamatical/logical symbols used to perform a mathamatical/logical operation such as addition , subtraction , division , AND , OR , NOT etc*

### C++ Operator Types :-

There are 6 types of operators in C++ :-

* Arithematic Operators :-

1) Addition -> +, adds two operands
2) Subtraction -> -, subtracts operand 2 from operand 1
3) Division -> /, divides operand 1 by operand 2
4) Multiplication -> *, multiplies operand 1 and operand 2
5) Modulo -> %, returns the remainder of an integer division
6) Increment(++) and Decreament(--) -> increase/decrease the value of an operand by 1 respectively

``` cpp
#include <iostream>
using namespace std;

int main() {
    int a = 8, b = 3;

    // Addition
    cout << "a + b = " << (a + b) << endl;
  
    // Subtraction
    cout << "a - b = " << (a - b) << endl;
  
    // Multiplication
    cout << "a * b = " << (a * b) << endl;
  
    // Division
    cout << "a / b = " << (a / b) << endl;
  
    // Modulo
    cout << "a % b = " << (a % b) << endl;
  
    // Increament
    cout << "++a = " << ++a << endl;
  
    // Decrement
    cout << "b-- = " << b--;
    
    return 0;
}
```
### ❄ Important Points :-
* *Modulo must only be used with integer operands, other operators can be used for integers.*
* *++a and a++ are both increment operators but in the former a is incremented first and then a is assigned, in the latter a is assigned first and then incremented.*
* *++ and -- are unary operators and require only one operand.*
* *while binary and ternary operators work on 2 and 3 operands respectively.*

...

* Relational Operators :-

*Used for comparison of values of two operands.*

1) Is equal to(==) :- checks if both the operands are equal by value.
2) Greater than(>) :- checks if operand one is greater than operand two by value.
3) Greater than or equal to(>=) :- checks if the first operand is greater than or equal to the second operand.
4) Less than(<) :- checks if operand one is smaller than operand two by value.
5) Less than or equal to(<=) :- checks if operand one is less than or equal to operand two.
6) Not equal to(!=) :- checks if operand one and two are not equal.

``` cpp
#include <iostream>
using namespace std;

int main() {
    int a = 6, b = 4;

    // Equal operator
    cout << "a == b is " << (a == b) << endl;
  
    // Greater than operator
    cout << "a > b is " << (a > b) << endl;
  
    // Greater than Equal to operator
    cout << "a >= b is " << (a >= b) << endl;
  
    //  Lesser than operator
    cout << "a < b is " << (a < b) << endl;
  
    // Lesser than Equal to operator
    cout << "a <= b is " << (a <= b) << endl;
  
    // Not equal to operator
    cout << "a != b is " << (a != b);

    return 0;
}
```
* Logical Operators :-
  
*Logical Operators are used to combine two or more conditions/statements or to compliment the original given condition, it returns boolean value True or False.*

1) Logical AND -> &&, returns True only if all operands are true or non-zero.
2) Logical OR -> ||, returns True if either of the operands are true or non-zero.
3) Logical NOT-> !, it is a unary operator meaning that it acts on only one operand. True is returned only if the operand is false or zero.
   
```cpp
#include <iostream>
using namespace std;

int main() {
    int a = 6, b = 4;

    // Logical AND operator
    cout << "a && b is " << (a && b) << endl;
  
    // Logical OR operator
    cout << "a || b is " << (a || b) << endl;
  
    // Logical NOT operator
    cout << "!b is " << (!b);

    return 0;
}
```

* Bitwise Operators :-
  
*Bitwise operators perform operations on individual bits which are obtained by compilation and conversion to bits.*

1) Bitwise AND -> &, copies bit to the result if it exists in both the operands.
2) Bitwise OR -> |, copies bit to the result if it exists in either of the operands.
3) Bitwise XOR -> ^, copies a bit to the result if it exists in either of the operands but not both.
4) Left Shift -> <<, shifts the value to the left by the number of bits specified by the right operand.
5) Right Shift -> >>, shifts the value to the right by the number of bits specified by the right operand.
6) One's (1's) Complement -> finds the complement which means that it returns True/1 if the operand is False/0 and vice versa.

#### ❄ Only int and char datatype can be used for bitwise operations.

```cpp
#include <iostream>
using namespace std;

int main() {
    int a = 6, b = 4;

    // Binary AND operator
    cout << "a & b is " << (a & b) << endl;

    // Binary OR operator
    cout << "a | b is " << (a | b) << endl;

    // Binary XOR operator
    cout << "a ^ b is " << (a ^ b) << endl;

    // Left Shift operator
    cout << "a << 1 is " << (a << 1) << endl;

    // Right Shift operator
    cout << "a >> 1 is " << (a >> 1) << endl;

    // One’s Complement operator
    cout << "~(a) is " << ~(a);

    return 0;
}
```

* Assignment Operators :-
  
*Assignment operators are used to assign a value to a variable , namely using a right operand to assign a value to a left operand.*

1) Assignment -> == , used to assign the value of the right operand to a left operand.
2) Add Assignment -> += , adds the right operand to left operand and assign the result to the left operand.
3) Subtract and Assignment -> -= , subtracts the right operand from the left operand and assigns the result to the left operand.
4) Multiply and Assignment -> *= , multiplies the right and left operands and assigns the result to the left operand.
5) Divide and Assignment -> /= , divides the left operand by the right operand and assigns the result to the left operand.

```cpp
#include <iosteam>
using namespace std;

int main() {
    int a = 6, b = 4;

    // Assignment Operator.
    cout << "a = " << a << endl;
  
    //  Add and Assignment Operator.
    cout << "a += b is " << (a += b) << endl;
  
    // Subtract and Assignment Operator.
    cout << "a -= b is " << (a -= b) << endl;
  
    //  Multiply and Assignment Operator.
    cout << "a *= b is " << (a *= b) << endl;
  
    //  Divide and Assignment Operator.
    cout << "a /= b is " << (a /= b);

    return 0;
}
```


* Ternary or Conditional Operators :-
  
*A conditional operator returns a value based on the condition and it takes 3 operands , hence known as Ternary Operators.*

#### ❄ Syntax of a ternary operator :-
Expression1 ? Expression2 : Expression3

#### ❄ Explaination of the above code :-

* the above operator takes Expression 1 one as an input
* if expression 1 is true then Expression 2 will be returned
* else if expression 1 is false then Expression 3 is returned

```cpp
#include <iostream>
using namespace std;

int main() {
    int a = 3, b = 4;

    // Conditional Operator
    int result = (a < b) ? b : a;
    cout << "The greatest number "
          "is " << result;

    return 0;
}
```

* Miscellaneous Operators :-
  
*Apart from these operators , there are some operators which are different from the above standard operators :-*

1) Sizeof Operator (sizeof) -> it is a unary operator used to compute the size of a variable or operand in bytes.
```cpp
sizeof (char);
sizeof (var_name);
```
2) Comma Operator(,) -> it is a binary operator and has multiple uses in c++ such as a seperator or used to evaluate the first operand and discard the result, evaluate the second result and discard the result and so on.
```cpp
int n = (m+1, m-2, m+5);
int a, b, c;
```
3) Addressof Operator(&) -> it is used to get the memory address of the location where a variable is stored, it is also used to create a reference.
```cpp
&var_name;
```
4) Dot Operator(.) -> used to access the members of a structure or a class object using their object names.
```cpp
obj . member;
```
5) Arrow Operator(->) -> used to access the variables of a class or a stucture through its pointer.
```cpp
sptr -> member;
```
6) Casting Operations -> casting operators are used to change the data type of a variable to another type without the variable losing its original value/signigficance.
```cpp
(float)x
static_cast<float>(x)
```
