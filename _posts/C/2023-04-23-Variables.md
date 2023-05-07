---
type: post
title: Variables
categories: [C, Introduction to C]
page: 4
---
## Variables Overview
A variable in C is simply named region of memory that contains a valua of a specific type. The name of the variable is used to access that value.

Some examples of primitive types in C are:
- `int` Whole numbers such as `1`, `785` and `-32`.
- `float` Real numbers with decimals like `1.5` or `578.489`.
- `char` Characters such as `a`, `Z`, `,` and `%`.

## Declaring Variables
Variables need to be declared with a type before they can be used. Here is an example of a variable declaration with the type `int`. Notice how it's written as type name and then semi-colon to end the line.
```c
// a variable of type int and name num will been created.
int num;
```
{: .nolineno }
## Assigning a value to a Variable
Now that we have created a variable we can assign to it. The assignment operator `=` is used to assign a value to our variable.
```c
// Assign the integer 5 to num and end with a semi-colon.
num = 5;
```
{: .nolineno }
## Accessing the value of a Variable
To access the value of a variable simply use it's name. Here is an example of what a program where we created a variable assign to it and then access it by printing it's value.
```c
# include <stdio.h>

int main() {
   int num;
   num = 5;
   print("num: %d", num);
   return 0;
}
```
Output:

`num: 5`
## Initializing a Variables
A variable must be delared before it can be used. Before the variable is assigned an initial value it has what ever random data was last in that memory location. This is commonly refered to as garbage data. Uninitialized variables in C contain garbage data. It is possible to declare a value while giving an inital value. This combines declaraion at assignment in a single line of code.
```c
// Seperate Declaration and Assignment.
int num;
num = 5;

// Initialization.
int num2 = 23;
```
{: .nolineno }
