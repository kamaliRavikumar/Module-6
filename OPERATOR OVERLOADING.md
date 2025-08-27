# Exp.No:27  
## Operator Overloading

---

### AIM  
write a python program to perform subtraction of two complex number using binary '+' operator overloading
class name : complex
Ob1 = complex(1, 2)
Ob2 = complex(2, 3)

---

### ALGORITHM

1. Start the program.
2. Define a class complex with two attributes: a (real part) and b (imaginary part).
3. Create a constructor __init__ to initialize the real and imaginary parts of the complex number.
4. Overload the subtraction operator __sub__ to subtract real parts and imaginary parts separately.
5. Return a new complex object with the result of subtraction inside __sub__.
6. Create two objects of class complex (Ob1 and Ob2) with user-defined values.
7. Perform subtraction using Ob1 - Ob2 which calls the overloaded operator.
8. Display the result in proper format (real + imaginary i).
---

### PROGRAM

```
class complex:
    def __init__(self,a,b):
        self.a = a
        self.b =b
    
    def __sub__(self,o):
        return self.a - o.a, self.b - o.b
        
Ob1 = complex(1, 2)
Ob2 = complex(2, 3)
Ob3 = Ob1 - Ob2
print(Ob3)

```

### OUTPUT

<img width="1050" height="257" alt="Screenshot 2025-08-27 145155" src="https://github.com/user-attachments/assets/bd88f2fe-dad3-414d-9139-b90ca514e90b" />

### RESULT
Thus the python program to perform subtraction of two complex number using binary '+' operator overloading is executed.
