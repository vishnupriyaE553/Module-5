# Exp.No:25  
## Hierarchical Inheritance

### AIM  
Write A Python Program to Calculated subraction using Inheritance.

### ALGORITHM

1. Begin the program.
2. Define a base class 'value' with methods to initialize and get basic details.
3. Define derived class 'subtract' that inherit from 'value', with methods to get and display their specific details.
4. Create objects of 'subtract' call their input and display methods.
5. Terminate the program.
### PROGRAM
```
Reg.No: 212223060305
Name: Vishnu priya E
class value:
    def get_values(self,a,b):
        self.a=a
        self.b=b
        self.c=a-b
class subtract(value):
    def sub(self):
        print(" subraction value1 : ",a)
        print(" subraction value2 : ",b)
        print("Subracted value :",self.c)
a=int(input()) 
b=int(input()) 
obj=subtract()
obj.get_values(a,b)
obj.sub()
```
### OUTPUT  
<img width="1013" height="307" alt="image" src="https://github.com/user-attachments/assets/0bbe4bed-4812-4757-98e0-80350bdbd1c9" />

### RESULT
Thus , a Python program to Calculate subraction using hierarchical inheritance is executed successfully.
