# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

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

---

## 🧪 Program

def factorial(n):     if n == 0 or n == 1: 
        return 1 
    return n * factorial(n - 1) 
 
def combination(n, k): 
    return factorial(n) // (factorial(k) * factorial(n - k)) 
 
# Step 2: Input from user 
num_rows = int(input()) 
print(' ' * (num_rows - i - 1), end='') 
for j in range(i + 1):         print(combination(i, j), end=' ') 
print() 
## Sample Output
<img width="269" height="322" alt="image" src="https://github.com/user-attachments/assets/a78de145-8c0d-4bd8-9d58-c458e6fea2a6" />

## Result
The program has been successfully executed
