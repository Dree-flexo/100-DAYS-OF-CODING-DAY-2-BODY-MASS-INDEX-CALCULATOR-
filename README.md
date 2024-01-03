# 100-DAYS-OF-CODING-DAY-2-BODY-MASS-INDEX-CALCULATOR-
"""
***********************************************
* Course : 100 Days OF Coding-Dr.Angela Yu     *                              *
* Author : Bright  Appiah                      *
* Day 1 - BODY MASS INDEX CALCULATOR                  *
* Date: 2024-01-03                             *
************************************************
"""

# 1ST Input weight in kilomaters
weight = input("Input weight : ")

# 2nd input height in meters
height = input("Input height : ")

# define data types
height = float(height)
weight = int(weight)

# insert body mass index formula
height = float(height)

# def function is used to introduce a user define function in code
# here, we craete our own square function
def square(height):
    result = height*height
    return result

BMI = weight / square(height)

# Change date type of BMI from float to string to allow for concatenation on our next line
# note: float and integers cannot be concatenated unless converted to strings
BMI= str(BMI)

print("Your body mass index is : " + BMI + " kg/m^2")

