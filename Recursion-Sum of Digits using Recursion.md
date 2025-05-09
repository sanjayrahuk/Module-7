# # 🔁 Recursion:Sum of Digits using Recursion in Python

## 🎯 AIM:
To write a Python program to calculate the **sum of all digits** in a number using **recursion**.

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `sum_digit(n)` that:
   - Returns 0 if `n <= 0` (Base Case)
   - Else, returns `n % 10 + sum_digit(n // 10)` (Recursive Case)
3. Take integer input from the user.
4. Call the recursive function and store the result.
5. Print the result.
6. **Stop**

## 💻 PROGRAM:
```
l = []

def SUM(n):
    if n == 0:
        return
    dig = n % 10
    l.append(dig)
    SUM(n // 10)

n = int(input("Enter a number: "))
SUM(n)
print("Sum of digits:", sum(l))
```
## OUTPUT
![441385766-7626a840-091a-4c89-ad05-5bc5f0545437](https://github.com/user-attachments/assets/9291c90d-3a14-4b29-b582-e006710ca96e)
## RESULT
Program successfully verified.
