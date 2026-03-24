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
Add Code Here
```
n = int(input("Enter number of rows: "))

for i in range(n):
    for j in range(n - i - 1):
        print(" ", end=" ")

    c = 1
    for j in range(i + 1):
        print(c, end="   ")
        c = c * (i - j) // (j + 1)

    print()
```

## Sample Output

<img width="1640" height="466" alt="image" src="https://github.com/user-attachments/assets/f325e541-0886-45ec-8598-3a2e45dcc77f" />


## Result
Thus, the Python program to generate Pascal's Triangle is executed successfully.
