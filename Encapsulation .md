# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
```
Developed By: Ashqar Ahamed S.T
Register No: 212224240018
```
```
class Rectangle:
    def __init__(self, length, breadth):
        self.__length = length
        self.__breadth = breadth

    def display(self):
        print("Length:", self.__length)
        print("Breadth:", self.__breadth)

rect = Rectangle(10, 5)
rect.display()
```
## Output

![Screenshot 2025-05-29 193334](https://github.com/user-attachments/assets/face20d0-cde0-4c7a-b0c7-1fa3d0a71b93)

To show that the variable is protected: 
![Screenshot 2025-05-29 193339](https://github.com/user-attachments/assets/9cf4bd70-1acf-4647-ba08-b76824a20d29)

## Result
Implementation **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth` was done successfully.
