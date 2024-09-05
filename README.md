# DATE:
#EXP NO: 5 Find the square root of a number
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
/*
Program to find the square root for the given number(newton's method) using function.

Developed by: M.VIRUMAA HARISH

RegisterNumber: 212223230246
*/
def newton_square_root(number):
    
    if number<0:
        
        print("Square root is not defined for negative numbers.")
   
    x=number/2.0
    
    while True:
        
        new_x=0.5*(x+number/x)
      
        if new_x==x:
            
            break
       
        x=new_x
    
    return x

number=int(input())

result=newton_square_root(number)

print(f"Square root of the number: {result}")

## Output:

![Screenshot 2024-09-05 091726](https://github.com/user-attachments/assets/f48dcd04-b768-44f3-9e19-3fafa65f034a)





## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
