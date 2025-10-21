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
```
def pascal_triangle(n):
    for i in range(n):
        print(" "*(n-i-1),end="")
        val=1
        for j in range(i+1):
            print(val,end=" ")
            val=val*(i-j)//(j+1)
        print()
n=int(input())
pascal_triangle(n)
```

## Sample Output
<img width="1920" height="1080" alt="Screenshot 2025-10-21 115132" src="https://github.com/user-attachments/assets/d0e0c635-a072-4f69-aa3f-b4d26010a2ff" />

## Result
successfully created  a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.
