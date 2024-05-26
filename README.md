# turtle_triangle_Python
# Drawing a triangle using a turtle module.

# Python program to draw a triangle 
# using Turtle Programming 
import turtle 
triangle = turtle.Turtle() 
  
triangle.forward(100) 

for i in range(2):
    triangle.left(120) 
    triangle.forward(100)

      
turtle.done()

# How does it work: 
# The turtle will go forward 100 pixels.

# To avoid repetition, for i in range() function is used.
