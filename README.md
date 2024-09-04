# Date:
# Ex.No.4: Find the GCD of two numbers

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
def gcd():
    num1 = int(input())
    num2 = int(input())
    
    while num2:
        num1, num2 = num2, num1 % num2
    
    print("GCD of two numbers is:",num1)
```

## Output:
![Screenshot 2024-09-04 160509](https://github.com/user-attachments/assets/dced91b3-2f2c-4770-82d4-3902a4a7b6fb)

## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
