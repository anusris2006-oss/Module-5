# Exp.No: 5A 
## Constructors - Parameterized Constructor

---

### AIM  
To write a Python code to create a class for a person with a parameterized constructor, which will take the `name` and `userid` of the person as parameters and print the `userid` of the person.

---

### ALGORITHM

1. Begin the program.  
2. Define a `person` class.  
3. The `person` class should have a parameterized `__init__` method that accepts two parameters: `name` and `userid`.  
4. Inside the `__init__` method, assign the `name` to `self.name` and the `userid` to `self.userid`.  
5. Print the `self.userid`.  
6. Prompt the user to enter their `name` (string) and `userid`.  
7. Create an instance `s1` of the `person` class by passing the entered `name` and `userid` to the constructor.  
8. Terminate the program.

---

### PROGRAM

```
#REG NO: 212223020002
#NAME:  ANUSRI SRIDHAR

class Person:
    # parameterized constructor
    def __init__(self, name, uid):
        self.name = name
        self.uid = uid

    # method to display user ID
    def display(self):
        print("User ID:", self.uid)


# take input from user
name = input()
uid = input()

# create object of Person class
p = Person(name, uid)

# call display method
p.display()

```

### OUTPUT
<img width="358" height="117" alt="image" src="https://github.com/user-attachments/assets/0b6d3434-ff19-4127-846b-b8a53fd74127" />

### RESULT
Thus the program to create a class for a person with a parameterized constructor has been implemented and executed successfully.
