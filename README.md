# Calculator-project
In this project, we will create a simple calculator program using Python that can perform basic mathematical operations such as addition, subtraction, multiplication, and division.

Step 1: Open a text editor or Python IDE

You can use any text editor or IDE to write your code. Some popular options include Visual Studio Code, PyCharm, and IDLE (which comes with Python).

Step 2: Define a function for each mathematical operation

We will define four functions, one for each mathematical operation. Here's an example of how to define the addition function:


def add(x, y):

    return x + y


This function takes two arguments (x and y) and returns their sum.

Here are the definitions of the other three functions:



def subtract(x, y):

    return x - y

def multiply(x, y):

    return x * y

def divide(x, y):

    return x / y



The subtract() function takes two arguments and returns their difference. The multiply() function takes two arguments and returns their product. The divide() function takes two arguments and returns their quotient.

Step 3: Write the main program

We will write the main program that prompts the user to input two numbers and the operation they want to perform, and then calls the appropriate function to perform the calculation. Here's an example:



print("Select operation.")

print("1.Add")

print("2.Subtract")

print("3.Multiply")

print("4.Divide")

choice = input("Enter choice(1/2/3/4): ")

num1 = int(input("Enter first number: "))

num2 = int(input("Enter second number: "))

if choice == '1':

    print(num1,"+",num2,"=", add(num1,num2))

elif choice == '2':

    print(num1,"-",num2,"=", subtract(num1,num2))

elif choice == '3':

    print(num1,"*",num2,"=", multiply(num1,num2))

elif choice == '4':

    print(num1,"/",num2,"=", divide(num1,num2))
    
else:

    print("Invalid input")
    
    
    

This code prompts the user to select the operation they want to perform, and then prompts them to enter two numbers. It then calls the appropriate function based on the user's choice and displays the result.

Step 4: Test your program

Save your code to a file with a .py extension (e.g. calculator.py) and run it from the command line or your IDE. Test your program by performing different calculations and making sure it provides the correct results.

That's it! You've just created a simple calculator program using Python. You can modify this code to add more features, like handling errors or performing more complex mathematical operations.
