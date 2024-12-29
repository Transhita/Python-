# Write a function is_prime(n) that checks if a number n is prime. Return True if it is, otherwise False.


def p(n):
   
    if n<=1:
    
        return False
    
    for i in range(2,n):
    
        if n%i==0:
        
            return False
        
        i+=1
   
    return True

print(p(11))

print(p(15))



![prime or not](https://github.com/user-attachments/assets/a3156ab1-fa7a-488d-8c69-51fe8d124deb)
