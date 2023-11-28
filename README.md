# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
###Step 1
 Define a function.
###Step 2 
Get the two numbers from the user.
###Step 3
Compare the two values, to find the smaller number.
###Step4
Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
#Program to find GCD of two number
#Developed by: DHANDEESWARAN SELVAKUMAR
#Register number: 23006838
def gcd():
    n1,n2=int(input()),int(input())
    if n1>n2:
        smaller=n2
    else:
        smaller=n1
    for i in range(1,smaller+1):
        if(n1%i==0 and n2%i==0):
             hcf=i
    print("GCD of two numbers is:",hcf)
```

## Output:
![GCD](https://github.com/dhandeeswaran2005/GCD-of-two-numbers/assets/147139188/f13899a7-eded-441c-b1f2-4b20a8f1210a)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
