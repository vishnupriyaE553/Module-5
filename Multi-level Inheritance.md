# Exp.No:24  
## Multi-level Inheritance

### AIM  
To write a Python program to Get the name, age and location of a person and display using Multilevel inheritance.

### ALGORITHM

1. Define the Person class:
         Inside the Person class, define the __init__ method (constructor) with two parameters: name and age.
         Inside the __init__ method, assign the name to self.name and age to self.age.
2. Define the Employee class that inherits from the Person class:
         Inside the Employee class, define the __init__ method (constructor) with three parameters: name, age, and location.
         Inside the __init__ method, call the __init__ method of the Person class using super() to initialize name and age.
          Assign location to self.location.
3. Define the DisplayDetails class that inherits from the employee class:
          Inside the DisplayDetails class, define the __init__ method (constructor) with three parameters: name, age, and person_id.
          Inside the __init__ method, call the __init__ method of the PersonDetails class using super() to initialize name, age, and location.
4. Inside the DisplayDetails class, define the show_details method:
          Inside the show_details method, return a formatted string with self.name, self.age, and self.location.
5. Prompt the user to enter name (string), age (integer), and location (string).
6. Create an instance person of the DisplayDetails class, passing name, age, and location to the constructor.
7. Call the show_details method on the person object and print the result.
8. Terminate the program.

### PROGRAM

```
Reg.No: 212223060305
Nmae: Vishnu Priya E
class Person:
    def get_name(self, name):
        self.name = name

class Employee(Person):
    def get_age(self, age):
        self.age = age

class Location(Employee):
    def get_location(self, location):
        self.location =location 

    def display(self):
        print(self.name, self.age, self.location)

name = input()
age = int(input())
location  = str(input())

person = Location ()
person.get_name(name)
person.get_age(age)
person.get_location(location)
person.display()

```
### OUTPUT
<img width="895" height="294" alt="image" src="https://github.com/user-attachments/assets/a18421cc-c585-4099-95b0-c853630b1c6f" />

### RESULT
Thus,a Python program to get the name, age, and location of a person and display them using multilevel inheritance are verified.
