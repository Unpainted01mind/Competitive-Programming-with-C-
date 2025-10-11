# What is C++ ?

### *C++ is a fast, compiled, low level language which is used in many applications such as :-*

* Compilers and GUI's , Operating Systems
* (HFT) High Frequency Trading systems
* has both low and high level features like OOP and manual memory management
* Similar syntax to C,C#
* high speed serves as a good choice for competitive programming

#### ❄ Below is a simple C++ program which prints Hello World :-

``` cpp
#include <iostream>
int main(){
  std::cout<<"Hello World"<<std::endl;
  return 0;
}
```
#### ❄ C++ was developed by Bjarne Stroustrup as an upgrade/enhancement of C.

### Features of C++ :-

* simple - Friendly/logical syntax
* machine Independent given that system has a compiler for it
* provides low level access to system resources
* fast execution speed hence preferred for competitive programming
* has object oriented features.

#### ❄ Below code shows identifiers being used for different entitities :-

``` cpp
#include <iostream>
#include <string>

class Student{
  //Identifiers being used for class and its variables.
  int roll_no;
  double marks;
  std::string name;
};
void display(int roll_no,double marks,std::string name){
  //Identifiers used to define a function.
  std::cout<<"Displaying Details"<<std::endl;
  std::cout<<"Name: "<<name<<std::endl;
  std::cout<<"ROll number: "<<roll_no<<std::endl;
  std::cout<<"Marks: "<<marks<<std::endl;
}
int main(){
  //Identifiers used to define main function variables.
  int r=10;
  double marks=100.00;
  std::string name="Alberto";
  display(r,marks,name);
  return 0;
}
```

### Naming conventions for C++ identifiers :-

1) Variables and Functions :-

* use camelCase , for constants use UPPER_SNAKE_CASE
* Ex - frequencyCount,studentMarks
* for functions use camelCase, Ex- getCount,isTrue 

2) Classes :-

* use PascalCase 
* Ex - Student_Details,Car,Bank_System


  



