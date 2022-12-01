from flag_elements import star, stripe

# Import the turtle graphics functions
from turtle import *

#set constant values

stripe_heigth = 80
flag_width = 600
flag_heigth = 400
union_heigth = 240
union_width = 300
star_size = 150

# Set up the drawing environment
setup(850, 600)
bgcolor('orange')
title('Fun with Flags')
setworldcoordinates(0, 0, flag_width, flag_heigth)
penup()

##### PUT YOUR CODE FOR DRAWING THE FLAG HERE - TOGO FLAG

#Flag Stripes
goto(0, stripe_heigth)
setheading(90)
for stripe_num in range(3):
    stripe(flag_width, stripe_heigth, 'green')
    forward(stripe_heigth * 2)

#Flag Union
goto(0, flag_heigth)
stripe(union_width, union_heigth, 'red')

#white star
goto(0 + 145, flag_heigth - 30)
star(star_size, 'white')

# Exit gracefully
hideturtle()
done()
