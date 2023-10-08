Program Aim:  

The aim of this program is to demonstrate the basic structure of a C++ program and print the message "Hello world!" along with "my first program" to the console.

Program Theory:  

#include<iostream>: This line includes the necessary header file <iostream> to enable input and output operations in the program.

using namespace std;: This line allows us to use the standard C++ library (std) without explicitly specifying it in the code. It simplifies the code by eliminating the need to prefix elements from the standard library with "std::".

int main(): This is the entry point of the program. All C++ programs start execution from the main function.

cout <<"hello world!" <<endl;: This line uses the cout (console output) stream to display the text "hello world!" to the console. <<endl is used to insert a newline character, so the next output will appear on a new line.

cout<<"my first program";: This line prints "my first program" to the console without adding a newline character, so it appears on the same line as the previous text.

return 0;: This statement indicates the successful termination of the program. The 0 return value signifies that the program executed without any errors.

Program Conclusion:

The program demonstrates the basic structure of a C++ program. When executed, it prints the following output to the console:


output:
 
![image](https://github.com/reetikasinghh/basics-of-c-/assets/139485681/036c0d52-5dae-49e1-a22c-f621d8418e03)




Program Aim:
The aim of this program is to create a simple calculator that can perform basic arithmetic operations (addition, subtraction, multiplication, and division) based on user input.

Program Theory:

#include <iostream>: This line includes the necessary header file <iostream> to enable input and output operations in the program.

using namespace std;: This line allows us to use the standard C++ library (std) without explicitly specifying it in the code. It simplifies the code by eliminating the need to prefix elements from the standard library with "std::".

int main(): This is the entry point of the program. All C++ programs start execution from the main function.

char op;: Declares a character variable op to store the operator (+, -, *, /).

float num1, num2;: Declares two floating-point variables num1 and num2 to store the numbers on which the operations will be performed.

cout << "Enter any operator: +, -, *, /: ";: Prompts the user to enter an operator.

cin >> op;: Reads the operator entered by the user.

cout << "Enter two numbers: ";: Prompts the user to enter two numbers.

cin >> num1 >> num2;: Reads the two numbers entered by the user.

switch(op): Begins a switch statement based on the operator entered by the user.

Inside the switch statement:

For each case (+, -, *, /), it performs the corresponding operation and displays the result.
The default case is used to handle any invalid operator input.
return 0;: This statement indicates the successful termination of the program with a return value of 0.
Program Algorithm:

Prompt the user to enter an operator (+, -, *, /).
Read the operator entered by the user.
Prompt the user to enter two numbers.
Read the two numbers entered by the user.
Use a switch statement to perform the appropriate operation based on the operator:
If +, calculate and display the sum.
If -, calculate and display the difference.
If *, calculate and display the product.
If /, calculate and display the quotient.
Handle any invalid operator input with an error message.
Terminate the program.
Program Conclusion:
This C++ program creates a basic calculator that can perform four arithmetic operations based on user input. The program prompts the user to enter an operator (+, -, *, /) and two numbers, and then it displays the result of the selected operation. If an invalid operator is entered, it displays an error message. The program demonstrates the use of switch statements and basic input/output operations in C++.




