# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
Program to find the square root for the given number(newton's method) using function.
Developed by: D.B.V.Sai Ganesh
RegisterNumber: 23009248 
n=int(input())
approx=0.5*n
for i in range(1,10):
    a=0.5*(approx+n/approx)
    approx=a
print("Square root of the number:",a)
```

## Output:
![image](https://github.com/saiganesh2006/Square-root-of-a-number/assets/145742342/f1c936ec-0e31-49d7-9084-ff076d52cc42)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
