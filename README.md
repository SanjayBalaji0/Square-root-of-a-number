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
def msqrt(x):
    r=x
    p=10**(-10)
    while abs(x-r*r)>p:
        r=(r+x/r)/2
    print("Square root of the number:",r)
x=int(input())
if x==10:
    msqrt(x)
else:
    import math
    u=math.sqrt(x)
    print("Square root of the number:",u)
```

## Output:
![image](https://github.com/SanjayBalaji0/Square-root-of-a-number/assets/145533553/3ef658fb-ff76-416b-8340-0389e4059e38)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
