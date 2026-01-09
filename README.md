
# calculator
simple calculator
def calculator():
    print("Simple Calculator")
    print("Operations:")
    print(" +  Addition")
    print(" -  Subtraction")
    print(" *  Multiplication")
    print(" /  Division")

    num1 = float(input("Enter first number: "))
    operator = input("Enter operator (+, -, *, /): ")
    num2 = float(input("Enter second number: "))

    if operator == "+":
        result = num1 + num2
    elif operator == "-":
        result = num1 - num2
    elif operator == "*":
        result = num1 * num2
    elif operator == "/":
        if num2 == 0:
            print("Error: Division by zero")
            return
        result = num1 / num2
    else:
        print("Invalid operator")
        return

    print("Result:", result)

calculator()
<img width="284" height="177" alt="download (1)" src="https://github.com/user-attachments/assets/967c9dc6-8efc-4553-8dd4-aba5304a7252" />
