# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
import math

class cse:
    def mech(self, r):
        c = math.pi * r**2
        print(f"Area of circle: {c:.2f}")

r = int(input("Enter radius: "))
ci = cse() 
ci.mech(r)
```

## Output

<img width="1046" height="512" alt="568239935-ba0ef66f-edf7-4613-8863-95b85deb06e3" src="https://github.com/user-attachments/assets/c2a7b0b4-133a-4122-b13c-b922cc144357" />

## Result
Thus, the program that calculates the area of a circle based on the radius provided by the user is executed successfully.
