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
/*
Program to find the gcd of two number using function.
Developed by: MANOJ G 
RegisterNumber: 212222240060
*/
def gcd():
    x=int(input())
    y=int(input())
    if x<y:
        small=x
    else:
        small=y
    for i in range(1,small+1):
        if(x%i==0 and y%i==0):
            gcd=i
    print("GCD of two numbers is:",gcd)        
```

## Output:

![image](https://github.com/Danielmanoj/GCD-of-two-numbers/assets/69635071/4d902a04-6c3d-4de7-bfc4-0c9c260bd0cb)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
