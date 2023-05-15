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
#Write a python Program to find the gcd of a number using function
#program was developed by:S.dinesh
#register number:212222230033
def gcd():
    num1,num2=int(input()),int(input())
    if num1>num2:
        smaller=num2
    else:
        smaller=num1
    for i in range(1,smaller+1):
        if num1%i==0 and num2%i==0:
            gcdvalue=i
    print("GCD of two numbers is:",gcdvalue)
```

## Output:
![Screenshot (56) pyt](https://github.com/Dineshsekhar2004/GCD-of-two-numbers/assets/119405916/436f799e-0fae-4070-bad3-52c40c002766)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
