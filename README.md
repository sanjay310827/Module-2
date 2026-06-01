# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim

To write a Python program to convert the number 16 into its binary representation using built-in Python functions.

## 🧠 Algorithm

Assign the value 16 to a variable a.
Use the built-in bin() function to convert the number to binary.
Print the result.

## 🧾 Program
```
a = 16
binary = bin(a)
print(binary)
```
## Output

<img width="1572" height="196" alt="Screenshot 2025-10-20 191837" src="https://github.com/user-attachments/assets/2d40e103-efb8-4514-aa6e-8da39a359091" />

## Result

Thus To write a Python program to convert the number 16 into its binary representation using built-in Python functions.
Hence the code has been executed successfully.

# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
```
def result(a, b):
    print(a % b)

a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

result(a, b)
```
## Output

<img width="1561" height="259" alt="Screenshot 2025-10-20 192349" src="https://github.com/user-attachments/assets/826d5b09-42cb-4fa6-9c46-e7f0fb6c9314" />


## Result

Thus To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.
Hence the code has been executed successfully.

# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

f = lambda x, y: x + y
print(f(a, b))

```
## Output

<img width="1557" height="185" alt="Screenshot 2025-10-20 192615" src="https://github.com/user-attachments/assets/169c2b00-1ae0-440c-8c57-b8eff0d87ad7" />

## Result

Thus To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.
Hence the code has been executed successfully.

# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

## 🧪 Program
```
def factorial(n):
    result = 1
    for i in range(2, n+1):
        result *= i
    return result

def combination(n, k):
    return factorial(n) // (factorial(k) * factorial(n - k))

rows = int(input("Enter the number of rows: "))

for i in range(rows):
    print(' ' * (rows - i - 1), end='')

    for j in range(i + 1):
        print(combination(i, j), end=' ')
    print()
```
## Output

<img width="1535" height="521" alt="Screenshot 2025-10-20 193623" src="https://github.com/user-attachments/assets/8bdc8e99-7820-4e76-87b1-4062d286254d" />

## Result

Thus To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.
Hence the code has been executed successfully.

## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm

1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
num = int(input("Enter a number: "))
temp = num
rev = 0

while temp > 0:
    rev = (10 * rev) + temp % 10
    temp = temp // 10

if rev == num:
    print("The number is a palindrome.")
else:
    print("The number is not a palindrome.")

```
## Output

<img width="1552" height="377" alt="Screenshot 2025-10-20 193909" src="https://github.com/user-attachments/assets/a96fad8c-b986-4eba-974f-e3c6abda2731" />

## Result

Thus To write a Python program that checks whether a given number is a **palindrome** using loops.
Hence the code has been executed successfully.
