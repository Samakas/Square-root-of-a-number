# Find the square root of a number

# DATE: 23/03/2024

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
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: Samakash.R.S
RegisterNumber: 212223230182
*/
def n_m(n,m=100):
    a=float(n)
    for i in range(m):
        n=0.5*(n+a/n)
    return n
a=int(input())
print("Square root of the number:",n_m(a))

```

## Output:
![alt text](<Screenshot 2024-04-06 110135.png>)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
