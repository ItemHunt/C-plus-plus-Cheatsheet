# C++ Documentation

## Temporary content: will be re-formatted.

## Table of Contents
### Libraries
- [iostream](https://github.com/ItemHunt/Learning-Hub/blob/master/languages/C%2B%2B/Cheatsheet.md#iostream)
### Documentation
- [General Codes](https://github.com/ItemHunt/Learning-Hub/blob/master/languages/C%2B%2B/Cheatsheet.md#input-and-output)
- [Mathematical Operators](https://github.com/ItemHunt/Learning-Hub/blob/master/languages/C%2B%2B/Cheatsheet.md#mathematical-operators)
- [Very Useful Codes](https://github.com/ItemHunt/Learning-Hub/blob/master/languages/C%2B%2B/Cheatsheet.md#very-useful-codes)
- [Data Types](https://github.com/ItemHunt/Learning-Hub/blob/master/languages/C%2B%2B/Cheatsheet.md#data-types)
- [Data Structures](https://github.com/ItemHunt/Learning-Hub/blob/master/languages/C%2B%2B/Cheatsheet.md#data-structures)
- [Loops and Related Codes](https://github.com/ItemHunt/Learning-Hub/blob/master/languages/C%2B%2B/Cheatsheet.md#loops-and-related-codes)
- [Conditions](https://github.com/ItemHunt/Learning-Hub/blob/master/languages/C%2B%2B/Cheatsheet.md#conditions)
- [Functions](https://github.com/ItemHunt/Learning-Hub/blob/master/languages/C%2B%2B/Cheatsheet.md#functions)

## Libraries 
- **iostream -** library used for input and output (eg. cout and cin). To use library, simply add the first two lines that can be found in the example below outside and on top of the main function *int main*. Note that *using namespace std;* is a global setting and may cause conflict with other codes from other libraries. It is recommended to use *std::* before every code related to the *iostream library* to solve the conflict problem. Ignore this warning if you are not using any other libraries.
<code>
#include <iostream>
using namespace std;

int main()
{
    //main C++ function
    return 0;
}
</code>



## Documentation
### Input and Output
- **cout << "Insert Message" << endl; -** Prints the message in-between the quotations onto the terminal, this code takes up one line. You can read the code as "cout or print this "text" and then end the line" This piece of code utilizes the iostream library
- **cin >> variable_name; -** Takes an input from the user and places the value into the target variable. You can read the code as "get user input and place it in the variable the programmer specified." Note that this command will not take values separated by space, it will only take the first chain of connected characters. This piece of code utilizes the iostream library
- **getline(cin, variable_name); -** Works the same way as the cin command except it takes the whole line of values that user creates. It is useful for getting sentences as a value since these are usually separated by spaces per word. This piece of code utilizes the iostream library

### Mathematical Operators
- **'+' (addition) -** operator for adding values, used in variables/cout to solve problems
- **'-' (subtraction) -** operator for subtracting values, used in variables/cout to solve problems
- **'*' (multiplication) -** operator for multiplying values, used in variables/cout to solve problems
- **'/' (division) -** operator for dividing values, used in variables/cout to solve problems
- **'%' (remainder) -** used to get the remainder of a problem after division
- **'==' (equals) -** used to describe equal, used in variables/cout/conditions to solve problems
- **'=' (assignment) -** used to assign a value to a variable
- **'++' (increments something by 1) -** used to increase the value of a variable by 1
- **'--' (decrements something by 1) -** used to decrease the value of a variable by 1
- **'<' (less than) -** used for creating conditions
- **'>' (greater than) -** used for creating conditions
- **'<=' (less than or equal to) -** used for creating conditions
- **'>=' (greater than or equal to) -** used for creating conditions
- **'!=' (not equal to) -** used for creating conditions
- **operator= (variableX = variableX + variableY) -** used as a shortcut to change the value of variablex by using variablex to interact with another variable. Examples of operator= are +=, -=, *=, and /=.

### Very Useful Codes
- **\n -** You can replace endl with this. To use it, put it right at the very end of the quotations of your cout command: example *cout << “Hello World\n”;*
- **//Hello, I am a comment -** Adding // makes the whole line located to the right of // a comment which the computer will not read. Very useful tool in making your program easy to understand or to temporarily disable certain parts of the program.
- **/* comment box */ -** 
Creates a comment box, everything that is in-between  /* and */  will be considered as a comment and the computer will not read this. Very useful tool in making your program easy to understand or to temporarily disable certain parts of the program.
- **&& -** stands for 'and' in programming. Useful for creating complex conditions
- **|| -** stands for 'or' in programming. Useful for creating complex conditions

### Data Types
- **int variable_name; -** used to create a variable that can only be assgined integer values
- **char variable_name; -** used to create a variable that can only be assigned character values (or only one character)
- **bool variable_name; -** used to create a variable that can only be assigned boolean values
- **string variable_name; -** used to create a variable that can only be assigned string values (or strings of characters)
- **double variable_name; -** used to create a variable that can only be assigned double values (decimal values with higher precision than float)
- **float variable_name; -** used to create a variable that can only be assigned float values (decimal values with lower precision than double)
- **&existing_variable_name; -** used to get the RAM address of an existing variable
- **'*'variable_with_RAM_Address; -** adding * before the name of an existing variable that contains the RAM address of another variable gets you the value of that another variable
- **auto variable_name; -** used to create a variable that changes its type depending on the value it contains. This variable does not function in a way thats exactly like single-purpose variables. It can only operate under special circumstances like in for loops.

### Data Structures
- **data_type array_name [x] = {a, b, c, ..N}; -** this is a basic array, simply assign it a data type at the start then its name. The value inside the brackets represent the number of elements that can exist in the array, no value means infinite. The next poriton after the '=' sign is the container that contains all the elements of the array. Here are two examples of a basic array: int basicarray [] = {1, 2, 3, 4, 5}; & int basicarray [5] = {1, 2, 3, 4, 5};
- **data_type array_name [x][y] = { {a, b, ..N}, {c, d, ..N}, {e, f, ..N} }; -** Basic arrays can be expanded into multiple dimensions. The one seen on the left is a two-dimensional array. Refer to the basic array for more info on the other segments, what will be explained here are y and the multiple groups inside the universal group. The value y represents the number of elements inside each subset of the universal set. The mini groups inside the universal group are subsets, all of which are separated by ','. Here is an example of a two-dimensional array: int twodimension [3][2] = { {1,2}, {3,4}, {5,6}};

### Loops and Related Codes
- **for (initialize_a_variable; counter_variable; event_per_loop) { code that will experience the loop } -** this is a for loop or a loop that ends after a specific number of runs or counts. To have a for loop, you need to initialize a new variable, add a condition or counter variable that decides when the loop continues and stop, and then an event that changes the value of the initialized variable after every loop which eventually reaches the conditions that state the loop should stop.
- **while (condition) { code that will experience the loop } -** this is a while loop. It is a loop that runs the specified code until the condition outputs false.
- **do { code that will experience the loop } while (condition); -** this is a do while loop. It works the same way as a while loop except the code always run at least once no matter if the condition outputs true or false.
- **break; -** this code helps you break out of an ongoing loop
- **continue; -** this code helps you break out of the current loop iteration and makes you continue on to the next iterations.

### Conditions
Note: Apparently, you don’t need {} when you do conditional operators. However, not using {} will result in the function only being connected to one piece of instruction. If you want more than one, your going to need the {}
- **if (condition) { code that will run if condition outputs true } -** this is a if statement, it is a piece of code that runs it's assigned block of code given that its condition outputs true.
- **else if (condition) { code that will run if condition outputs true } -** this is a else if statement, it works the same way as a if statement except this piece of code can only be used right after a if statement or else if statement. Its a component of a connected structure of conditions (if and else if statements)
- **else { code that will run if condition outputs true } -** this is a else statement, it works similarly with if and else if statements except it can only be used once in a connected structure of conditions and it only runs at the very end of that structure. It is a conditional statement that runs a block of code given that all if and else if conditions above it outputted false. 
- **switch (variable_x) { case #: variable_y = value; break; default: variable_y = value; } -** this is a switch, it switches the value of variable_y depending on the value of variable_x. You can have as many cases as you want, the # stands for number. If variable_x equals that case value then variable_y will equal to the value you specified under those conditions. Default is the final part of the switch, it works similarly with a else statement. 