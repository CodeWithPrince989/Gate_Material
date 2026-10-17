

C language is developed in 1978 in bell laborartry. initially c language is use for system development only but later on c language is use in many thing. C++ and Java is made up of c Language.

#### Identifier in C Language
- Identifier are basically name of program element like array, variable, functions etc.
- There is a rules for name a Identifier:
    1. Special CHaracters are Not allowed like(#,$, @ ..) except "_".
    2. C language is case sensitive so FIRST is defferent from first.
    3. 2 Successive undersrore are not allowed.
    4. predefined keyword use not allowed.
    5. Character Length should not be greater than 31 if greater then the compiler will take only 31 character only.
    6. avoid use of underscore at first character of identifier.


#### Keyword in C Language
- Keyword are predefined or reserved word in c language that fixed meaning and by convention the keyword is written in lowercase.

#### Datatypes in C Language
- Basic Datatypes in C     
    1. char         1           store charater
    2. int          4           store integer values less than 10^9
    3. float        4           store floating values less than 10^9
    4. double       8           store floating values greater than 10^9

- Basic Datatypes and their Variants
    1. char         1           store number upto -128 to 127.
    2. unsigned char1           store positive part 0 to 255.
    3. signed char  1           store -128 to 127.
    4. int          4           -10^5 to 10^5.
    5. unsigned int 4            0 to 10^9.
    6. signed int   4

#### Conntant and Variables

- Constant are those values which do not change have fixed valued.

            const pi = 3.14

- Variables are thos value which change when we change in our program.

Ex:  int i = 1;                     
    /    |   \
Datatype |    Constant
     Variable


#### Our First Program

#include<stdio.h>
int main(){
    printf("\n Welcome to the world of C ");// prints the message on the screen
    return 0; // returns a value 0 to the operating system
}

- here the stdio.h is a in-build library of taking input and giving output in the screen.

