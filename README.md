# Create-a-rotating-circle-pattern-with-colors
Draw a rotating spiral circle pattern with colorsin python turtle🐢


import turtle
t = turtle.Turtle()
t.pensize(2)
t.speed(0)
for i in range(6):
  for colours in ["red","magenta","pink","green","white","blue","yellow"]:
    t.color(colours)
    t.circle(100)
    t.left(10+i)
turtle.hideturtle()
