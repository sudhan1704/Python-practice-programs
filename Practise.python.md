# Python-practice-programs

# Arithmetical operations
 
 ## Basic operations (add, sub, mul & divide)
 
 
## Store input numbers:
      
num1 = input('Enter first number: ')  
num2 = input('Enter second number: ')  
  
  - Add two numbers  
    
sum = float(num1) + float(num2)  

  - Subtract two numbers 
    
min = float(num1) - float(num2) 

  - Multiply two numbers  
    
mul = float(num1) * float(num2)  

  - Divide two numbers  
     
div = float(num1) / float(num2)  

#Display the sum  
    
print('The sum of {0} and {1} is {2}'.format(num1, num2, sum))  

#Display the subtraction  

print('The subtraction of {0} and {1} is {2}'.format(num1, num2, min))  

#Display the multiplication  

print('The multiplication of {0} and {1} is {2}'.format(num1, num2, mul))  

#Display the division  

print('The division of {0} and {1} is {2}'.format(num1, num2, div))  

------------------------------------------------------------------------------------------------------------------------------------------------


## Swaping two variables


P = int( input("Please enter value for P: "))  
Q = int( input("Please enter value for Q: "))  
   
#To swap the value of two variables  
#we will user third variable which is a temporary variable  
temp_1 = P  
P = Q  
Q = temp_1  
   
print ("The Value of P after swapping: ", P)  
print ("The Value of Q after swapping: ", Q)  


--------------------------------------------------------------------------------------------------------------------------------------

## Generating a Random Number

import random  
n = random.random()  
print(n)  


## Generating a number within a given range

import random  
n = random.randint(0,50)  
print(n)  

----------------------------------------------------------------------------------------------------------------------------------------

## Check a number is positive, negative or zero


#Default function to run if else condition  
def NumberCheck(a):   
    #Checking if the number is positive  
    if a > 0:   
        print("Number given by you is Positive")   
    #Checking if the number is negative   
    elif a < 0:   
        print("Number given by you is Negative")   
    #Else the number is zero  
    else:   
        print("Number given by you is zero")  
#Taking number from user  
a = float(input("Enter a number as input value: "))  
#Printing result  
NumberCheck(a)  

--------------------------------------------------------------------------------------------------------------------------------

## Check a number is odd or even

num = int(input("Enter a number: "))  
if (num % 2) == 0:  
   print("{0} is Even number".format(num))  
else:  
   print("{0} is Odd number".format(num))  
   
-----------------------------------------------------------------------------------------------------------------------------------
   

## To find a factorial of a number

num = int(input("Enter a number: "))    
factorial = 1    
if num < 0:    
   print(" Factorial does not exist for negative numbers")    
elif num == 0:    
   print("The factorial of 0 is 1")    
else:    
   for i in range(1,num + 1):    
       factorial = factorial*i    
   print("The factorial of",num,"is",factorial)    
   
-----------------------------------------------------------------------------------------------------------------------------


## To find the sum of natural numbers

num = int(input("Enter a number: "))  
  
if num < 0:  
   print("Enter a positive number")  
else:  
   sum = 0  
   #use while loop to iterate un till zero  
   while(num > 0):  
       sum += num  
       num -= 1  
   print("The sum is",sum)  
   
   --------------------------------------------------------------------------------------------------------------------
   








