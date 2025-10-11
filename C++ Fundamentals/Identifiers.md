# C++ Identifiers

**Identifiers are basically unique names given to functions,variables,structs and such entities so that they can be used in our program.**

### The below program uses a,b,sum as the names for our variables.

``` cpp
#include <iostream>

int main(){
    int a=10;
    int b=20;
    int sum=a+b;
    std::cout<<"The sum is: "<<sum<<std::endl;
    return 0;
}
```

### Rules for naming identifiers :-

* an identifier can only contain letters (A-Z), numbers(0-9),underscores(_). Special characters/spaces are not allowed
* an identifier cannot begin with a number, it can only begin with a letter or an underscore.
* a keyword cannot be used as an identifier as it has a predefined meaning withing the programming language , doing so would result in a compilation error. Ex-> using int as an identifier is not valid as int is a reserved keyword which is used to hold integer values
* an identifier must be unique in its namespace
* cpp is a case sensitive language 

