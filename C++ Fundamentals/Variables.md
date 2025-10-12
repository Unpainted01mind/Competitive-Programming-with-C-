# C++ Variables :-

### *A variable is a name given to a memory location , it is the basic storage unit in a programming language whose value can be accessed/modified before/during the execution of a program.*


#### ❄ Below code shows us an example of a variable :-

```cpp
#include <iostream>
int main(){
    int age=10;//age variable to store age of the person

    std::string name="John";//name used to store a string 
    if(age>=18){
        std::cout<<name<<" is eligible to vote!\n";// \n makes succeding characters to be displayed in the next line.
    }
    else{
        std::cout<<name<<" is in-eligible to vote!\n";
    }
    //here we access the name variable and print it.
    return 0;
}
```

### Creating a variable :-

#### ❄ Syntax:-

*type name=value*

*here type is the datatype of the variable, name is the identifier used to denote it a name/identity , name variable stores the given value*

#### ❄ Examples :-

```cpp
int sum=20;//sum is a variable used to store values of int type such as 1,2,3,20 etc.

//multiple variables of same type can be created as follows :-
int var1,var2,var3;
```
#### ❄ Working :-

*here the keyword int tells the compiler to store values of type int inside the variable sum*




