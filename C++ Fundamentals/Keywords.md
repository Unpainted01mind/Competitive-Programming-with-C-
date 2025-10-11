# C++ Keywords

### *Keywords are reserved words which have a predefined/special meaning within the language hence they cannot be redefined for other purposes.Ex- int,float,double,cout,cin,endl.*

#### ❄ Below code shows us some basic keywords in C++ :-

``` cpp
#include <iostream>

int main(){
    int id=2095;//int for storing integers,whole numbers.
    double marks=195.259;//double for storing decimals upto a larger precision.
    std::string name="John";//string for storing a sequence of characters.

    std::cout<<"The name is: "<<name<<std::endl;
    return 0;
}
```

### Categorisation of Keywords :-

|Category|Keyword|
|--------|-------|
|Data Types|bool , char , char8_t ,char16_t , char32_t , long , short , int , unsigned , signed , float , double , void , wchar_t|
|Control Flow|if , else , switch , case , default , for , while , continue , goto|
|Boolean & Null|true , false , nullptr|
|Memory Management|new , delete , alignas ,   alignof , sizeof|
|Classes & Structs|class , struct , enum , mutable , this , friend|
|Access Specifiers|public , private , protected|
|Functions & Modifiers|inline , explicit , virtual , override , constexpr , consteval , constinit , operator , typedef , using , typename|
|Templates & Generics|template , concept  , requires|
|Exception Handling|try , catch , throw , noexcept|
|Casting & type info|const_cast ,  dynamic_cast , reinterpret_cast ,  static_cast , decltype , typeid|
|Constants & Storage|const , static , static_assert , extern , register , thread_local , volatile|
|Modules/Export|export , namespace|
|Coroutines(C++20)|co_await , co_return , co_yield|
|Operators(alternate spellings)|and , and_eq , or , or_eq , not , not_eq , bitand , bitor , compl , xor , xor_eq|
|Miscellanous|asm , auto , return , sizeof|
