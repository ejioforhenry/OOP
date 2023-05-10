# Object-Oriented Programming

The goal of OOP is to write clean code.

## Sample code

```
class Employee:
    def __init__(self, name, age, salary):
        self.name = name
        self.age = age
        self.salary = salary
        
    def add_age(self):
        self.age += 1
        
    def get_age(self):
        return "Age is {}".format(self.age)
```
## Pillars of OOP

- Encapsulation
- Inheritance
- polymorphism
- Abstraction