# Input Function

`input()` function is used to take input from the user during the execution of a program. The `input()` function reads a line of text from the user as a "string" and returns that "string". It allows the user to provide input interactively.

```py
# Getting input from the user
user_input = input("Enter something: ") # returns "string"
print("You entered:", user_input)
```

```py
# Get user input as an integer
user_number = int(input("How old are you: "))

# Perform some operation with the input
result = user_number * 2
print("Twice the entered number:", result)
```

```py
user_input = input("Enter something: ") # returns "string"
print("You entered:", user_input)
```

---

## Program

Write a program that prompts the user to enter their name using input("What is your name? ") Store the entered name in a variable and then print a greeting message that incorporates the name (e.g., "Hello, [name]!").

```python
name = input("What is your name? ")

print("Hello, " + name + "!")
```
