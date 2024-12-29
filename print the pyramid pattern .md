# print the pyramid pattern 

r=int(input("Enter number of row :\n"))

print(r)

for i in range(1,r+1):
 
     for j in range(1,r-i+1):
    
        print(" ", end ="")
  
     for j in range(1,2*i):
   
        print("*",end="")
    
     print()

![print the pyramid pattern 1,3,5,7,9](https://github.com/user-attachments/assets/224fbc61-5df2-463f-8d82-68dfcd5f8fc7)
