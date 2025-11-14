# Simple-Calculator
# 🧮 Simple Python Calculator

This is a simple command-line calculator written in Python.  
It allows the user to enter two numbers and choose an arithmetic operation: **addition, subtraction, multiplication, or division**.

---

## 📌 Features
- Takes two numeric inputs from the user  
- Supports four operations: `+`, `-`, `*`, `/`  
- Handles invalid choices  
- Handles division by zero safely  

---

## 💻 Code Example

```python
a = int(input("NO.1 = "))
b = int(input("NO.2 = "))
choice = input("Enter your choice (+, -, *, /): ")

if choice == "+":
    print(a + b)
elif choice == "-":
    print(a - b)
elif choice == "*":
    print(a * b)
elif choice == "/":
    if b != 0:
        print(a / b)
    else:
        print("Error: Division by zero")
else:
    print("Invalid choice")
