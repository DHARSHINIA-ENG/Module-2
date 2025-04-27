# Exp.No:2e  
## SEB - SUM OF THE GIVEN SERIES 

---

### AIM  
To write a Python Program to find the sum of series 1+3+5+7.......+N 

---

### ALGORITHM

1. Begin the program.  
2. Get the input a drom the user
3. store sum=0
4. For i in range of 1 to a+1
5. if i is an odd number
6. Add the numbers
7. Atlast print the final number

---

### PROGRAM

```
a=int(input())
sum=0
for i in range(1,a+1):
    if i%2!=0:
        sum+=i
print("The sum of the series = ",sum)
```
### OUTPUT
![image](https://github.com/user-attachments/assets/7b66b061-f85e-4ddf-977e-a0ccb089fc6b)


### RESULT
Thus the Python Program to find the sum of series 1+3+5+7.......+N has been executed successfully.
