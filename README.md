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
Developed by: Azeez Ahamad
RegisterNumber: 23003977
def newton_square_root(n):
    x=n
    for _ in range(10):
        x=0.5*(x+n/x)
    return x
    
num = float(input(""))
result=newton_square_root(num)
print("Square root of the number:", result)

```

## Output:
![image](https://github.com/AzeezBT/Square-root-of-a-number/assets/150319523/c67d5b7d-9a13-4756-be58-4826cfbab11a)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
