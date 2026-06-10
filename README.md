# 🐍 Python OOP — Object-Oriented Programming Full Course

A complete, beginner-friendly course on Object-Oriented Programming (OOP) in Python.
This repository covers every OOP concept from scratch with clear examples, exercises,
and real-world use cases — structured for easy learning step by step.

---

## 📌 Repository Info

- Title       : python-oop-course
- Description : A complete Object-Oriented Programming course in Python — covering classes,
                objects, inheritance, encapsulation, polymorphism, abstraction, and more.
- Language    : Python 3.x
- Level       : Beginner to Advanced

---

## 📚 Course Outline

### 🟢 Module 1 — Introduction to OOP
- What is OOP and why use it?
- OOP vs Procedural Programming
- The 4 Pillars of OOP (overview)

### 🟢 Module 2 — Classes & Objects
- Defining a Class
- Creating Objects (Instances)
- The __init__() Constructor
- Instance Variables vs Class Variables
- The `self` keyword

### 🟡 Module 3 — Methods
- Instance Methods
- Class Methods (@classmethod)
- Static Methods (@staticmethod)
- The __str__() and __repr__() Methods

### 🟡 Module 4 — Encapsulation
- Public, Protected, and Private Attributes
- Getters and Setters
- The @property Decorator
- Name Mangling in Python

### 🟡 Module 5 — Inheritance
- Single Inheritance
- Multi-level Inheritance
- Multiple Inheritance
- The super() Function
- Method Overriding
- The MRO (Method Resolution Order)

### 🔴 Module 6 — Polymorphism
- What is Polymorphism?
- Method Overriding (Runtime Polymorphism)
- Duck Typing in Python
- Operator Overloading (Dunder Methods)

### 🔴 Module 7 — Abstraction
- Abstract Classes (abc module)
- Abstract Methods
- Interfaces in Python

### 🔴 Module 8 — Advanced OOP
- Magic / Dunder Methods (__len__, __add__, __eq__, etc.)
- Class Decorators
- Dataclasses (@dataclass)
- Slots (__slots__)
- Composition vs Inheritance

---

## 📁 Folder Structure

python-oop-course/
│
├── 01_intro/
│   ├── what_is_oop.py
│   └── oop_vs_procedural.py
│
├── 02_classes_objects/
│   ├── creating_class.py
│   ├── constructor_init.py
│   └── instance_vs_class_vars.py
│
├── 03_methods/
│   ├── instance_methods.py
│   ├── class_methods.py
│   └── static_methods.py
│
├── 04_encapsulation/
│   ├── access_modifiers.py
│   ├── getters_setters.py
│   └── property_decorator.py
│
├── 05_inheritance/
│   ├── single_inheritance.py
│   ├── multiple_inheritance.py
│   ├── super_function.py
│   └── method_overriding.py
│
├── 06_polymorphism/
│   ├── runtime_polymorphism.py
│   ├── duck_typing.py
│   └── operator_overloading.py
│
├── 07_abstraction/
│   ├── abstract_class.py
│   └── abstract_methods.py
│
├── 08_advanced/
│   ├── dunder_methods.py
│   ├── dataclasses.py
│   └── composition_vs_inheritance.py
│
└── README.md

---

## 🚀 How to Use

1. Clone this repository:
   git clone https://github.com/your-username/python-oop-course.git

2. Go into any module folder:
   cd 02_classes_objects

3. Run any Python file:
   python creating_class.py

---

## 💡 Example Sneak Peek

# Simple Class Example
class Car:
    def __init__(self, brand, model):
        self.brand = brand
        self.model = model

    def display_info(self):
        print(f"Car: {self.brand} {self.model}")

my_car = Car("Toyota", "Corolla")
my_car.display_info()
# Output: Car: Toyota Corolla

---

## 🛠 Requirements

- Python 3.x (No external libraries needed)
- A code editor like VS Code or PyCharm (recommended)

---

## 📜 Topics Covered (Quick Reference)

| Topic              | Module   | File                        |
|--------------------|----------|-----------------------------|
| Classes & Objects  | Module 2 | creating_class.py           |
| Inheritance        | Module 5 | single_inheritance.py       |
| Encapsulation      | Module 4 | access_modifiers.py         |
| Polymorphism       | Module 6 | duck_typing.py              |
| Abstraction        | Module 7 | abstract_class.py           |
| Magic Methods      | Module 8 | dunder_methods.py           |

---

## 👨‍💻 Author

Your Name
GitHub: https://github.com/your-username

---

## 📜 License

This project is open-source and available under the MIT License.

---

## ⭐ Support

If this course helped you, please give the repository a star on GitHub!
It motivates to keep creating free content.
