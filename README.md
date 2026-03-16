📘 Python Program: Inheritance Example (Animal, Dog, Cat)

📌 Overview

This Python program demonstrates Inheritance, an important concept of Object-Oriented Programming (OOP).

A parent class (Animal) is created with a method speak().
Two child classes (Dog and Cat) inherit the behavior from the parent class.

Inheritance allows one class to reuse the properties and methods of another class.

⚙️ Source Code
class Animal:
    def speak(self):
        print("Animal make sound")

class Dog(Animal):
    pass
        
class cat(Animal):
    pass

d = Dog()
d.speak()

🧠 How the Program Works
1️⃣ Parent Class
class Animal:

Animal is the base (parent) class.

It contains a method speak().

2️⃣ Parent Method
def speak(self):
    print("Animal make sound")

This method prints a message when called.

3️⃣ Child Class (Dog)
class Dog(Animal):
    pass

Dog inherits from Animal.

pass means no additional code is added.

It automatically gets access to the speak() method.

4️⃣ Child Class (Cat)
class cat(Animal):
    pass

cat also inherits from Animal.

It can use the same methods from the parent class.

(Note: In Python, class names usually start with a capital letter, so Cat would be preferred.)

5️⃣ Create an Object
d = Dog()

d is an object of the Dog class.

6️⃣ Call the Method
d.speak()

Even though Dog does not define speak(), it inherits the method from Animal.

▶️ Output
Animal make sound
🔑 Key Concepts Demonstrated

Classes

Inheritance

Parent class (Base class)

Child class (Derived class)

Method reuse

pass keyword

🚀 Improved Version (More Realistic)
class Animal:
    def speak(self):
        print("Animal makes sound")

class Dog(Animal):
    def speak(self):
        print("Dog barks")

class Cat(Animal):
    def speak(self):
        print("Cat meows")

d = Dog()
c = Cat()

d.speak()
c.speak()

Output:

Dog barks
Cat meows

This example shows method overriding, where child classes provide their own implementation.

📚 Learning Outcome

After studying this program, you will understand:

How inheritance works in Python

How child classes reuse methods from parent classes

The role of base and derived classes

<img width="534" height="679" alt="image" src="https://github.com/user-attachments/assets/e1b3ea82-f207-4eb1-8768-68592d71a7fd" />

