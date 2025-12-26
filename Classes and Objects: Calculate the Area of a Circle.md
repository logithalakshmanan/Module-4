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
import math
class pen():
    def stationary(self,radius):
        a=math.pi*radius**2
        return a
s=pen()
radius=float(input())
b=s.stationary(radius)
print(f"Area of circle: {b:.2f}")

## Output
Input	Expected	Got	
50
Area of circle: 7853.98
Area of circle: 7853.98
10
Area of circle: 314.16
Area of circle: 314.16


## Result
area of circle is calculated using class and objects

