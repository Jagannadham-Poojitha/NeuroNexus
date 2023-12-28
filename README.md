# NeuroNexus
#TASK 2 - CALCULATOR

'''Design a simple calculator with basic arithmetic operations. Prompt the user to input two numbers and
an operation choice. Perform the calculation and display the result.'''
def add(n1, n2):
    return n1 + n2

def subtract(n1, n2):
    return n1 - n2

def multiply(n1, n2):
    return a * b

def divide(n1, n2):
    if n2 != 0:
        return n1 / n2
    else:
        return "Cannot divide by zero"

print("Welcome to the Calculator!")
a1 = float(input("Enter  first number: "))
a2 = float(input("Enter  Second number: "))

print("Select operation:")
print("1. Addition")
print("2. Subtraction")
print("3. Multiplication")
print("4. Division")

choice = input("Enter choice (1/2/3/4): ")

if choice in ('1', '2', '3', '4'):
    if choice == '1':
        print("Result:", add(a1, a2))
    elif choice == '2':
        print("Result:", subtract(a1, a2))
    elif choice == '3':
        print("Result:", multiply(a1, a2))
    elif choice == '4':
        print("Result:", divide(a1, a2))
else:
    print("Invalid input")
    
