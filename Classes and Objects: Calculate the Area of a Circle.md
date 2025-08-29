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
    def mech(self,rad):
        area=math.pi*rad**2
        return area
if __name__=="__main__":
    rad=float(input())
    obj=cse()
    area=obj.mech(rad)
    print(f"Area of circle: {area:.2f}")
```

## Output
<img width="1197" height="292" alt="image" src="https://github.com/user-attachments/assets/c0b80f2c-6a32-4a8e-a844-e14a0e440b19" />

## Result
Thus the program is executed successfully.
