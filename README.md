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
#Write a python program to find the square root for the given number(newton's method) using function.
#Developed by: M.tharun kumar
#reg no:212222100056
def sq(number,number_iters=100):
    a=float(number)
    for i in range(number_iters):
        number=0.5*(number+a/number)
    return number
a=int(input())
print("Square root of the number:",sq(a))
 
    
    
```

## Output:

![2023-05-24 (1)](https://github.com/25tharunkumar/Square-root-of-a-number/assets/123470785/ee98055a-0294-4d7a-847e-22d3ca82f32f)





## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
