# Write a Python program that generates the first n numbers of the Fibonacci sequence.


def fib(n):
  
    a=0
    
    b=1
    
    for i in range(n):
    
        a,b=b, a+b
    
    return a

for i in range(10):

    print(fib(i))



![fibonacci](https://github.com/user-attachments/assets/15576fa5-cfeb-4495-9bda-f9c91a622217)
