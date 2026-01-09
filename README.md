![Screenshot_20250903_094919_Ludo King](https://github.com/user-attachments/assets/73556f27-8585-41a7-895a-74adb023ebd9)
![Screenshot_20250903_094919_Ludo King](https://github.com/user-attachments/assets/2f7d21d9-0140-4423-9b83-027dd9db5e7d)
![Screenshot_20250903_094919_Ludo King](https://github.com/user-attachments/assets/fa4aa80b-a288-4585-8bd8-c3e9beae1092)
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
<img width="900" height="900" alt="pngwing com" src="https://github.com/user-attachments/assets/69118014-ccf8-4ff8-8e1d-f5fcbe1094d5" />
