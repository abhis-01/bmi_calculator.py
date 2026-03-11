# bmi_calculator.py
A simple Python project that calculates Body Mass Index (BMI) using height and weight.
# BMI Calculator

weight = float(input("Enter your weight in kg: "))
height = float(input("Enter your height in meters: "))

bmi = weight / (height ** 2)

print("Your BMI is:", bmi)

# Category
if bmi < 18.5:
    print("You are Underweight")
elif bmi < 25:
    print("You are Normal weight")
elif bmi < 30:
    print("You are Overweight")
else:
    print("You are Obese")
