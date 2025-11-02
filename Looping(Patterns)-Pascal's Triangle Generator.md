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
rows = int(input()) <br />
coef = 1<br />

for i in range(1, rows+1):<br />
    for space in range(1, rows-i+1):  <br />
        print(" ",end="") <br />
    for j in range(0, i):   <br />
        if j==0 or i==0:  <br />
            coef = 1  <br />
        else:  <br />
            coef = coef * (i - j)//j  <br />
        print(coef, end = " ")  <br />
    print()

## Sample Output
<img width="586" height="669" alt="image" src="https://github.com/user-attachments/assets/4a82a543-f54a-4399-84ff-18ace60c3ff0" />


## Result
Thus,the Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user is created successfully.
