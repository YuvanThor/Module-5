# # Constructors in Python: Welcome Message with Student Name

## 🎯 Aim
To write a Python program that creates a **Student** class with a **default constructor** and a method to display a welcome message along with the student’s name provided by the user.

## 🧠 Algorithm
1. **Get user input**: Accept the student's name from the user.
2. **Define the class**: Create a class `Student` with a default constructor (`__init__`).
3. **Default Constructor**: In the constructor, assign the user input (student name) to an instance variable `self.a`.
4. **Display Message**: Define a method `show` that prints "This is non-parameterized constructor" and a welcome message with the student’s name.
5. **Execute the Program**: Instantiate the `Student` class and call the `show` method.

## 🧾 Program

class Calculation1:
    def Summation(self, a, b):
        return a + b

class Calculation2:
    def Subtraction(self, a, b):
        return a - b

class Derived(Calculation1, Calculation2):
    def Division(self, a, b):
        if b != 0:
            return a / b
        else:
            return "Error: Division by zero"

a = int(input())
b = int(input())
obj = Derived()

print(obj.Summation(a, b))
print(obj.Subtraction(a, b))
print(obj.Division(a, b))


## Output
<img width="1259" height="246" alt="image" src="https://github.com/user-attachments/assets/69f3b9e9-2d0f-418c-8934-7f6e7eb1e17d" />

## Result
Thus the program demonstrates multiple inheritance by performing basic arithmetic operations — Addition, Subtraction, and Division — using three classes has been executed successfully.
