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
''' 
Program to find the gcd of two number using function.
Developed by: sriharan jv
Register number: 212223100054
'''
    
def gcd():
    a,b=int(input()), int (input())
    if a>b:
        smaller=b
    else:
        smaller=a
    for i in range(1,smaller+1):
        if(a%i==0 and b%i==0):
            hcf =i
    print("GCD of two numbers is:",hcf)

*/
```

## Output:
![image](https://github.com/sriharan23000516/GCD-of-two-numbers/assets/139841769/51c42486-72a1-4b11-b29a-107b584de735)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
