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
~~~
n = int(input())
for i in range(1,n+1):
    c=1
    for j in range(1,i+1):
        print(c,end=' ')
        c = c*(i-j)//j
    print()
~~~

## Sample Output
<img width="765" height="596" alt="image" src="https://github.com/user-attachments/assets/42fbf12a-4af0-4c23-ba5c-5a9113b82cae" />


## Result
Thus , the program has been executed successfully.

