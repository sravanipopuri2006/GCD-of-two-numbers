# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
#GCD of two numbers
#developed by: Popuri Sravani
#Register number : 23006561
def gcd():
    num1=int(input())
    num2=int(input())
    c=0
    t=min(num1,num2)
    for i in range(1,t):
        if num1%i==0 and num2%i==0:
            c=i
    print("GCD of two numbers is:",c)

```

## Output:
![Alt text](<gcd p.png>)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
