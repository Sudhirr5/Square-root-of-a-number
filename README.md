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
```python
#find the square root for the given number(newton's method)
#Developed by: R SUDHIR KUMAR
#Register number: 23000604
a=int(input())
aprox=0.5*a
for i in range(1,10):
    x=0.5*(aprox+a/aprox)
    aprox=x
print('Square root of the number:',x)
```

## Output:
![gcd of two number](scr5.png)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
