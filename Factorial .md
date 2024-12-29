# Write a function calculate_factorial(n) that takes a number n and returns its factorial using a loop.

def f(n):
  
    fact=1
   
    for i in range(n,1,-1):
     
        fact *=i
  
    return fact

n=int(input("Enter a number:\n"))

print(n,"is",f(n))



![factorial](https://github.com/user-attachments/assets/130db1c9-88b3-40f4-a1b1-bc65ef039017)
