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

````
# Encapsulation Example

class Rectangle:

    def __init__(self):
        self.__length = 10
        self.__breadth = 5

        print("Length =", self.__length)
        print("Breadth =", self.__breadth)

# Main Program
r = Rectangle()

````
## Output

<img width="546" height="157" alt="image" src="https://github.com/user-attachments/assets/e1549c7b-c832-4500-9a92-a7f2a3f5d48d" />


## Result

Thus, the concept of Encapsulation was successfully implemented in Python by defining private member variables __length and __breadth inside the Rectangle class.
