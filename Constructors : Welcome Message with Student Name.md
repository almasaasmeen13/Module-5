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

~~~
class student:
    def __init__(s):
        print('This is non parametrized constructor')
    def display(self,a):    
        print('Hello',a)
a=input()
q=student()
q.display(a)
~~~
## Output
<img width="890" height="250" alt="image" src="https://github.com/user-attachments/assets/53cad903-80ed-4f3a-84cb-24cbbaa94a52" />

## Result
Thus, the program has been successfully executed.
