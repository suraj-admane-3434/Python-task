# Python-task
##################task 1###################################
# Take input from the user
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

# Perform basic mathematical operations
addition = num1 + num2
subtraction = num1 - num2
multiplication = num1 * num2

# Handle division carefully to avoid division by zero
if num2 != 0:
    division = num1 / num2
else:
    division = "Undefined (cannot divide by zero)"

# Display the results
print("\nResults:")
print("Addition: ", addition)
print("Subtraction: ", subtraction)
print("Multiplication: ", multiplication)
print("Division: ", division)

#####################task 2#############################
# Step 1: Take user's first name and last name as input
first_name = input("Enter your first name: ")
last_name = input("Enter your last name: ")

# Step 2: Concatenate first name and last name into full name
full_name = first_name + " " + last_name

# Step 3: Print a personalized greeting message
print("Hello, " + full_name + "! Welcome!")
