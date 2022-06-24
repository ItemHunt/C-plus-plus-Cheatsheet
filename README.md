# C++ Cheatsheet

## Introduction
The C++ Cheatsheet repository is a place where you can view a cheatsheet for C++, a programming language that is regularly used for creating desktop applications, operating systems, and such. You can also find useful pieces of information here (especially for beginners) and learning resources which are related to C++ in one way or another. This repository is a mini-project for a much bigger project called the [*Learning-Hub Project*](https://github.com/ItemHunt/Learning-Hub). 

## How to Contribute
I welcome any contributors to this mini-project. Feel free to fork the project and add/edit stuff here and send out a pull request for review. If all is good, I should approve the pull request. In case you are new to GitHub, refer to [CONTRIBUTING](CONTRIBUTING.md) for a more detailed guide.

## Contributors
<a href="https://github.com/ItemHunt/C-plus-plus-Cheatsheet/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ItemHunt/C-plus-plus-Cheatsheet" />
</a>

<!-- Contributors section made with [contrib.rocks](https://contrib.rocks). -->

## Table of Contents
### Libraries
- [iostream](https://github.com/ItemHunt/Learning-Hub/blob/master/languages/C%2B%2B/Cheatsheet.md#iostream)
### Cheatsheet
- [General Codes](https://github.com/ItemHunt/Learning-Hub/blob/master/languages/C%2B%2B/Cheatsheet.md#input-and-output)
- [Mathematical Operators](https://github.com/ItemHunt/Learning-Hub/blob/master/languages/C%2B%2B/Cheatsheet.md#mathematical-operators)
- [Very Useful Codes](https://github.com/ItemHunt/Learning-Hub/blob/master/languages/C%2B%2B/Cheatsheet.md#very-useful-codes)
- [Data Types](https://github.com/ItemHunt/Learning-Hub/blob/master/languages/C%2B%2B/Cheatsheet.md#data-types)
- [Data Structures](https://github.com/ItemHunt/Learning-Hub/blob/master/languages/C%2B%2B/Cheatsheet.md#data-structures)
- [Loops and Related Codes](https://github.com/ItemHunt/Learning-Hub/blob/master/languages/C%2B%2B/Cheatsheet.md#loops-and-related-codes)
- [Conditions](https://github.com/ItemHunt/Learning-Hub/blob/master/languages/C%2B%2B/Cheatsheet.md#conditions)
- [Functions](https://github.com/ItemHunt/Learning-Hub/blob/master/languages/C%2B%2B/Cheatsheet.md#functions)


## Libraries 
- **iostream -** library used for input and output (eg. cout and cin)

## Cheatsheet
### Input and Output
- **cout << "Insert Message" << endl; -** outputs a message onto the terminal
- **cin >> variable_name; -** requests for input that is not separated by spaces from the user
- **getline(cin, variable_name); -** requsts for input from the user

### Mathematical Operators
- **'+' (addition) -** operator for adding values
- **'-' (subtraction) -** operator for subtracting values
- **'*' (multiplication) -** operator for multiplying values
- **'/' (division) -** operator for dividing values
- **'%' (remainder) -** used to get the remainder of a problem after division
- **'==' (equals) -** used to describe equal
- **'=' (assignment) -** used to assign a value to a variable
- **'++' (increments something by 1) -** used to increase the value of a variable by 1
- **'--' (decrements something by 1) -** used to decrease the value of a variable by 1
- **'<' (less than) -** used for creating conditions
- **'>' (greater than) -** used for creating conditions
- **'<=' (less than or equal to) -** used for creating conditions
- **'>=' (greater than or equal to) -** used for creating conditions
- **'!=' (not equal to) -** used for creating conditions
- **operator= -** used as a shortcut to change the value of variables by using variables to interact with another variable. Examples of operator= are +=, -=, *=, and /=.

### Very Useful Codes
- **\n -** Replacement for endl
- **//Hello, I am a comment -** creates a comment line
- **/* comment box */ -** 
creates a comment box
- **&& -** stands for 'and'
- **|| -** stands for 'or'

### Data Types
- **int variable_name; -** used to create variables for integers
- **char variable_name; -** used to create variables for characters
- **bool variable_name; -** used to create variables for boolean
- **string variable_name; -** used to create variables for strings
- **double variable_name; -** used to create variables for double values
- **float variable_name; -** used to create variables for float values
- **&existing_variable_name; -** used to get the RAM address of an existing variable
- **'*'variable_with_RAM_Address; -** used to get the value located in a specific RAM address
- **auto variable_name; -** used to create a variable that changes its data type depending on the value it contains.

### Data Structures
- **data_type array_name [x] = {a, b, c, ..N}; -** basic array, a data structure used to store a group of a specific type of data
- **data_type array_name [x][y] = { {a, b, ..N}, {c, d, ..N}, {e, f, ..N} }; -** two-dimensional array, a data structure used to store group/s of a specific type of data, can be expanded into multiple more dimensions

### Loops and Related Codes
- **for (initialize_a_variable; counter_variable; event_per_loop) { code that will experience the loop } -** for loop which loops a code structure for a specific number of times
- **while (condition) { code that will experience the loop } -** while loop which loops a code structure under specified conditions
- **do { code that will experience the loop } while (condition); -** do while loop which loops a code structure under specified conditions, always runs the code structure at least once regardless if the condition outputs true/false
- **break; -** break out of a loop
- **continue; -** skip/disregard current loop an continue to the next iteration

### Conditions
- **if (condition) { code that will run if condition outputs true } -** if statement, runs a block of code if the condition outputs true
- **else if (condition) { code that will run if condition outputs true } -** else if statement, runs a block of code if the condition outputs true and if the previous if or else if statements outputted false.
- **else { code that will run if condition outputs true } -** else statement, runs a block of code if all previous conditions before it outputted false
- **switch (variable_x) { case #: variable_y = value; break; default: variable_y = value; } -** switch statement, runs a specific block of code depending if variable_x matches any of the values of the cases otherwise it runs the default block of code.

### Functions
- **void function_name (parameter/s if applicable) { insert block of code that runs when this function is called } -** void function, used to run a block of code without having it return a value.
- **data_type function_name (parameter/s if applicable) { insert block of code that runs when this function is called followed by 'return specificed_variable;' } -** return function, used to run a block of code and have it return a value
- **class_name (new parameters that will be connected to the class parameters) { Insert all public variables and make them equal the new parameters: create a return function to call private variables } -** constructer fuction, used to easily create objects with classes.

### Classes and Objects

Class -
class (class name)
{
Private:
(Input private class attributes that are inaccessible to anything but the class); (Private variables cannot be accessed by any part of the code except the class)
Public:
(input public class attributes that are accessible to any part of the code); (Public variables can be accessed by any part of the code)
};
Description: C++ doesn’t have a lot of variable data types, it cant fit it all. The purpose of the class is to act as a data type for something that can’t be described by a singular data type. Another purpose of a class is to act as a schematic or plan to create an object in the program.
Example:
class Phone
{
Private:
string androidVersion;

Public:
string speed;
string brand;
string RAM;
};

Class calling and giving values in int main
Using the example, you can call a class or its components by doing this
Phone Phone1;
Phone1.speed = “input”;
Phone1.brand = “input”;
Phone1.RAM = “input”;
cout << Phone1.speed << endl;
You cant access/modify androidVersion in int main
Output
Input
More elaboration: You give out values to the class attributes in int main, but you cant do that with private variables and the writing style for giving out values to the attributes is tedious. That can be fixed with the addition of functions inside of the classes. The functions will allow private variables to receive values since it is inside the class. Refer to functions, or constructors to be more specific for more details





## Other Codes

(string variable name).length(); (This will find the total number of characters within the string)
(variable name)[index number]; (This will display the character in the indicated index position. Computers start counting at 0 from left to right, typically used for strings, arrays, and prob some others)

(string variable name).find(specific characters you want to find, index position to start the search); (This will allow you to look for specific characters starting at a specific index position.)

(string variable name).subtr(insert starting index position, insert ending index position); (This will get a segment of a string and display it, its called substring)

Inheritance - class (new class name) : (public/private) (existing class name){[insert new attributes);}; it allows the new class to receive the same attributes of an existing class and allows you to input new attributes

Advance Math Codes
Description: Uses source code file cmath, #include (cmath) uses namespace std;
Code list: https://www.programiz.com/cpp-programming/library-function/cmath
Examples:
pow (base number, exponent);
sqrt(number);
round(number);
ceil(number);
floor(number);




## Additional Information For C++
- In conditional statements like if, else, and else if: it is not necessary to always use curly brackets. If the code connected to the conditional statement is only a one liner, then you don't need curly brackets however if it is more than one line then you need curly brackets.
- For new C++ codes, it is recommended that you explore the different C++ libraries and then find a cheatsheet for them or a guide/documentation.

## Learning Resources List
- Free Code Camp C++ Tutorial for Beginners - Full Course (video) https://www.youtube.com/watch?v=vLnPwxZdW4Y
- Tutorialspoint C++ Tutorial (website) https://www.tutorialspoint.com/cplusplus/index.htm
- Azure Cloud C++ development (website) https://azure.microsoft.com/en-in/develop/cpp/
- OS development with C++ (video) https://www.youtube.com/watch?v=AsSMKL5vaXw
- Game development with C++ (video) https://www.youtube.com/watch?v=iEn0ozP-jxc
- Unreal Engine 4 with C++ (video) https://www.youtube.com/watch?v=qeKDRqWtGV0
- Other C++ project ideas (website) https://hackr.io/blog/cpp-projects