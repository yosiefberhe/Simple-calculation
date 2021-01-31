# Simple-calculation
# Write a program, with comments, to calculate different parameters of geometric shapes:

#  Ask the user to what type of shape they want to specify, circle or square. The user should
# enter ‘c’ for circle and ‘s’ for square.
# a) If the user enters ‘c’:
# i. ask the user to enter the radius (r) of the circle. Assume the user will enter a valid
# numeric value.
# ii. Calculate the area = 3.14*r^2
# and display the area rounded to 1 decimal place, with a
# s uitable message.
# iii. Calculate the circumference = 2*3.14*r and display the circumference rounded to
# nearest integer, with a suitable message.
# b) Otherwise, if the user enters ‘s’:
# i. ask the user to enter the length (s) of one side of the square. Assume the user will enter
# a valid numeric value.
# ii. Calculate the area = s^2
# and display the area rounded to 1 decimal place, with a
# suitable message.
# iii. Calculate the perimeter = 4*s and display the perimeter rounded to nearest integer,
# with a suitable message.
# c) Otherwise, print the string “You did not enter a valid choice for shape.”


#Question 2

C= "circle"

S="square"

pi = 3.14

# Getting an input from user for shape

shape=input("Please enter a type of shape: ")

#if statements 

if shape==C: print(C)

radius=int(input("Please input the radius in order to get area and circumference: "))

#Calculating the values of Area and Circumference 

Area = (pi*radius*radius)

Circumference = (2*pi*radius)

print("Area = " + str(round(Area, 1)))

print("Circumference = " + str(round(Circumference, 0)))


if shape==S: Side=input("Please enter the length of one of the sides: ")

#Calculating the values of Area and Perimeter

Area_2 = (Side * Side)

Perimeter = (4 * Side)

print("Area = " + str(round(Area_2, 1)))

print("Perimeter = " + str(round(Perimeter, 1)))

#If user did not enter the right letters such us c and s, it prints error.
else:
print("You did not enter a valid choice for shape.")







