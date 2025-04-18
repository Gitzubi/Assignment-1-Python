# Assignment-1-Python
All Python Assignments from tutedude


Task 1: Perform Basic Mathematical Operations

Problem Statement: Write a Python program that does the following:
1.  Takes two numbers as input from the user.
2.  Performs the basic mathematical operations on these two numbers:
o	Addition
o	Subtraction
o	Multiplication
o	Division
3.  Displays the results of each operation on the screen.

ANS: 
num_1= input("Enter First Number: ")
num_2= input("Enter second number: ")
num_1= int(num_1)
num_2= int(num_2)
addition= num_1 + num_2
subtraction= num_1 - num_2
multiplication= num_1 * num_2
division= num_1 / num_2
print("addition: ", addition)
print("subtraction: ", subtraction)
print("multiplication: ", multiplication)
print("division: ", division)

Output: 
Enter First Number: 21
Enter second number: 7
addition:  28
subtraction:  14
multiplication:  147
division:  3.0
============================================


Task 2: Create a Personalized Greeting

Problem Statement: Write a Python program that:
1.  Takes a user's first name and last name as input.
2.  Concatenates the first name and last name into a full name.
3.  Prints a personalized greeting message using the full name.

ANS:
first_name= input("Enter your First Name: ")
last_name= input("Enter your Last Name: ")
full_name= first_name + " " + last_name
print("Hello, " + full_name + "!" + " Welcome to the Python Program")


Output:
Enter your First Name: Zubair
Enter your Last Name: Ahmed
Hello, Zubair Ahmed! Welcome to the Python Program



