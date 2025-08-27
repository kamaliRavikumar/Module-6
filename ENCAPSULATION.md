# Exp.No:29  
## Encapsulation

---

### AIM  
To write a Python program to create a class `Student` with the private members `name` and `age`, and add getter and setter methods to initialize and modify the `age` variable.

---

### ALGORITHM

1. **Start the Program.**
2. **Define the `Student` class.**
   - Inside the `Student` class, define the `__init__` method to initialize `name` and the private member `__age`.
3. **Define a getter method** `get_age` to return the value of the private member `__age`.
4. **Define a setter method** `set_age` to set a new value to the private member `__age`.
5. **Create an object `stud`** of the `Student` class with the name 'Jessa' and age 14.
6. **Print the name and the age** of `stud` using the getter method.
7. **Use the setter method** `set_age` to change the age of `stud` to 16.
8. **Print the name and the updated age** of `stud` using the getter method.
9. **End the program.**

---

### PROGRAM

```
class Student:
    def __init__(self, name, age):
        self.__name = name      # private variable
        self.__age = age        # private variable

    # Getter method for name
    def get_name(self):
        return self.__name

    # Getter method for age
    def get_age(self):
        return self.__age

    # Setter method for age
    def set_age(self, age):
        self.__age = age

# Create an object of Student
stu = Student("Jessa", 14)

# Display initial details
print("Name:", stu.get_name(), stu.get_age())

# Update age using setter
stu.set_age(16)

# Display updated details
print("Name:", stu.get_name(), stu.get_age())



```

### OUTPUT

<img width="967" height="288" alt="Screenshot 2025-08-27 144753" src="https://github.com/user-attachments/assets/372837bb-bb6f-4247-b54f-b6b34274faf7" />

### RESULT
Thus the Python program to create a class `Student` with the private members `name` and `age`, and add getter and setter methods to initialize and modify the `age` variable is created and executed.



