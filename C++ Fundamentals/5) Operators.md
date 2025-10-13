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


