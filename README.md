def print_result(operation, result):
    print(f"The result of the {operation} is {result}.")

def multiply_numbers(a, b):
    return a * b

def add_numbers(a, b):
    return a + b

# Input from user
first_number = int(input("What is your first number: "))
second_number = int(input("What is your second number: "))

# Multiplication
multiplication_result = multiply_numbers(first_number, second_number)
print_result("multiplication", multiplication_result)

# Addition
addition_result = add_numbers(first_number, second_number)
print_result("addition", addition_result)
