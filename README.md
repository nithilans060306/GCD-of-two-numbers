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
```python
/*
Program to find the gcd of two number using function.
Developed by: Nithilan S
RegisterNumber: 212223240108
*/
def gcd():
    a = int(input())
    b = int(input())
    if(a<b):
        s = a
    else:
        s = b
    for i in range(1,s+1):
        if(a%i==0 and b%i==0):
            ans = i
    print(f"GCD of two numbers is: {ans}")
```

## Output:
![Screenshot 2024-03-27 155845](https://github.com/nithilans060306/GCD-of-two-numbers/assets/147473026/aec44919-8b81-4ea0-9a34-6b2cca581074)
## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
