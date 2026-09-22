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
n = float(input("Enter a number: "))
x = n        # initial guess

for i in range(10):   # iterate fixed number of times
    x = 0.5 * (x + n / x)

print("Square root =", x)

Developed by:K Santhosh 
RegisterNumber:  212225040041

```

## Output:

<img width="735" height="343" alt="image" src="https://github.com/user-attachments/assets/f258ec74-5c3f-4597-b3b8-a816b626e8aa" />


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
