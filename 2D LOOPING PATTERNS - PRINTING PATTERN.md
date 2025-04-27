# Exp.No:2d
## LOOPING PATTERNS - PYRAMID PATTERN

---

### AIM  
To write a Python Program to print pyramid pattern of numbers .Get the input for the number of rows 

---

### ALGORITHM

1. Begin the program.  
2. Input integer a
3. For each i from 0 to a - 1, do:
4. For each j from 0 to i, do:
5. Print j + 1 followed by a space (on the same line)
6. After inner loop ends, print a newline
7. End
---

### PROGRAM
```
a=int(input())
for i in range(0,a):
    for j in range(0,i+1):
        print(j+1,end=" ")
    print()

```

### OUTPUT
![image](https://github.com/user-attachments/assets/fc3fe6bd-7a74-430b-a465-438956f1f636)

### RESULT
Thus the Python Program to print pyramid pattern of numbers has been implemented and executed successfully.
