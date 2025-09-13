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
        area = math.pi * r * r
        print("Area of circle: {:.2f}".format(area))

radius = float(input())
obj = cse()
obj.mech(radius)
```

## Output

<img width="986" height="311" alt="Screenshot 2025-09-13 231219" src="https://github.com/user-attachments/assets/294470ca-5ecf-45d0-9850-d31a36373c79" />


## Result
Thus, the program to calculate the area of a circle using Classes and Objects in Python was executed successfully.
