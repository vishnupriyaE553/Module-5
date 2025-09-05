# Exp.No:21  
## Constructors - Parameterized Constructor

### AIM  
Write a Python code to create a Class for a Person with the parameterised constructor which will take the name and userid of the person as parameters print the userid  of the person,

### ALGORITHM

1. Begin the program.  
2. Define a `person` class.  
3. The `person` class should have a parameterized `__init__` method that accepts two parameters: `name` and `userid`.  
4. Inside the `__init__` method, assign the `name` to `self.name` and the `userid` to `self.userid`.  
5. Print the `self.userid`.  
6. Prompt the user to enter their `name` (string) and `userid`.  
7. Create an instance `obj` of the `person` class by passing the entered `name` and `userid` to the constructor.  
8. Terminate the program.

### PROGRAM
```
Reg.No: 212223060305
Name: Vishnu Priya E

class person:
    def __init__(self,name,userid):
        self.name=name
        self.userid=userid
    def display(self):
        print(self.userid)
name=str(input())
userid=str(input())
obj=person(name,userid)
obj.display()
```

### OUTPUT
<img width="758" height="261" alt="image" src="https://github.com/user-attachments/assets/fb33bf94-e8b9-4977-a7a3-789879de7951" />

### RESULT
Thus,a Python code to create a class for a person with a parameterized constructor are verified.
