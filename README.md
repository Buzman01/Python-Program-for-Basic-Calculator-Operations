# Python-Program-for-Basic-Calculator-Operations
A Function is the simple callable object in python. A function can accept some arguments and possibly return some object. The following python code represents the basic calculator operation like addition, subtraction, multiplication and division. The code is well organized with different functions.
# menu() function prints the main menu, and prompts for a choice
def menu():
    #print what options you have
    print "Welcome to calculator in Python"
    print "your options are:"
    print " "
    print "1) Addition"
    print "2) Subtraction"
    print "3) Multiplication"
    print "4) Division"
    print "5) Quit calculator"
    print " "
    return input ("Choose your option: ")

# this adds two numbers given
def add(a,b):
    print a, "+", b, "=", a + b

# this subtracts two numbers given
def sub(a,b):
    print b, "-", a, "=", b - a

# this multiplies two numbers given
def mul(a,b):
    print a, "*", b, "=", a * b

# this divides two numbers given
def div(a,b):
    print a, "/", b, "=", a / b

# NOW THE PROGRAM STARTS, AS CODE IS RUN
loop = 1
choice = 0
while loop == 1:
    choice = menu()
    if choice == 1:
        add(input("Add this: "),input("to this: "))
    elif choice == 2:
        sub(input("Subtract this: "),input("from this: "))
    elif choice == 3:
        mul(input("Multiply this: "),input("by this: "))
    elif choice == 4:
        div(input("Divide this: "),input("by this: "))
    elif choice == 5:
        loop = 0

print "Thankyou for using calculator!"

# End of the program
 

OUTPUT:

Welcome to calculator in Python
your options are:
 
1) Addition
2) Subtraction
3) Multiplication
4) Division
5) Quit calculator
 
Choose your option: 1
Add this: 25
to this: 35
25 + 35 = 60
Welcome to calculator
your options are:
 
1) Addition
2) Subtraction
3) Multiplication
4) Division
5) Quit calculator
 
Choose your option: 3
Multiply this: 15
by this: 10
15 * 10 = 150
Welcome to calculator
your options are:
 
1) Addition
2) Subtraction
3) Multiplication
4) Division
5) Quit calculator
 
Choose your option: 5
Thankyou for using calculator!

