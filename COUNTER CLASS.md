# Exp.No:30  
## COUNTER CLASS

---

### AIM  
Create two specific classes- Beans and Mango. Along with that, Create a generic function that tells us the type and color of the object we pass. Mind you, since we have passed only “obj” through it, this obj can be any object.

---

### ALGORITHM

1. Start the program.
2. Define a class Beans with two methods:
    type() → prints "Vegetable".
    color() → prints "Green".
3. Define another class Mango with two methods:
    type() → prints "Fruit".
    color() → prints "Yellow".

4. Create a generic function func(obj) that takes any object as input.
5. Inside func(obj), call obj.type() to display whether the object is a vegetable or fruit.
6. Next, call obj.color() to display the color of the object.
7. Create objects:
8. obj_beans from class Beans.
9. obj_mango from class Mango.
10. Call the generic function func() for both objects to display their type and color.

---

### PROGRAM

```
class Beans(): 
     def type(self): 
       print("Vegetable") 
     def color(self):
       print("Green") 
class Mango(): 
     def type(self): 
       print("Fruit") 
     def color(self): 
       print("Yellow")      
def func(obj): 
       obj.type()
       obj.color()
#creating objects
obj_beans = Beans() 
obj_mango = Mango() 
func(obj_beans) 
func(obj_mango)

```

### OUTPUT
<img width="1084" height="336" alt="Screenshot 2025-08-27 145726" src="https://github.com/user-attachments/assets/26559e5d-d7e7-4212-bbde-d10be2878233" />


### RESULT
Thus to Create two specific classes- Beans and Mango. Along with that, Create a generic function that tells us the type and color of the object we passis created and executed.
