1. What will be the output?
   ```python
   import turtle
   turtle.shape('turtle')
   ```
1. What will be the output?
   ```python
   import turtle
   turtle.shape('turtle')
   turtle.setup(500,500)
   ```
1. What will be the output?
   ```python
   import turtle
   turtle.shape('turtle')
   turtle.setup(500, 500)
   turtle.penup()
   turtle.Screen().bgcolor('blue')
   ```
1. What will be the output?
   ```python
   import turtle
   turtle.shape('turtle')
   turtle.setup(500, 500)
   turtle.penup()
   turtle.Screen().colormode(255)
   turtle.Screen.bgcolor(29,162,216)
   ```
1. What will be the output?
   ```python
   import turtle
   turtle.shape('turtle')
   turtle.setup(500, 500)
   turtle.penup()
   turtle.Screen().colormode(255)
   turtle.Screen.bgcolor(29,162,216)
   turtle.color(9,185,13)
   ```
1. What will be the output?
   ```python
   import turtle
   turtle.shape('turtle')
   turtle.setup(500, 500)
   turtle.penup()
   turtle.Screen().colormode(255)
   turtle.Screen.bgcolor(29,162,216)
   turtle.color(9,185,13)
   turtle.pencolor(0,128,0)
   ```
1. What will be the output?
   ```python
   import turtle
   turtle.shape('turtle')
   turtle.setup(500, 500)
   turtle.penup()
   turtle.Screen().colormode(255)
   turtle.Screen.bgcolor(29,162,216)
   turtle.color(9,185,13)
   turtle.pencolor(0,128,0)
   turtle.turtlesize(10,10,2)
   ```
1. What will be the output?
   ```python
   import turtle
   turtle.shape('turtle')
   turtle.setup(500, 500)
   turtle.penup()
   turtle.Screen().colormode(255)
   turtle.Screen.bgcolor(29,162,216)
   turtle.color(9,185,13)
   turtle.pencolor(0,128,0)
   turtle.resizemode('auto')
   ```
1. What will be the output?
   ```python
   import turtle
   turtle.shape('turtle')
   turtle.setup(500, 500)
   turtle.penup()
   turtle.Screen().colormode(255)
   turtle.Screen.bgcolor(29,162,216)
   turtle.color(9,185,13)
   turtle.turtlesize(outline=3)
   ```
1. what will be the output?
   ```python
   import turtle
   turtle.shape('turtle')
   turtle.setup(500, 500)
   turtle.penup()
   turtle.Screen().colormode(255)
   turtle.Screen.bgcolor(29,162,216)
   turtle.color(9,185,13)
   turtle.forward(200)
   ```
1. What will be the output?
   ```python
   import turtle
   turtle.shape('turtle')
   turtle.setup(500, 500)
   turtle.penup()
   turtle.Screen().colormode(255)
   turtle.Screen.bgcolor(29,162,216)
   turtle.color(9,185,13)
   turtle.backward(200)  
   ```
1. What will be the output?
   ```python
   import turtle
   turtle.shape('turtle')
   turtle.setup(500, 500)
   turtle.penup()
   turtle.Screen().colormode(255)
   turtle.Screen.bgcolor(29,162,216)
   turtle.color(9,185,13)
   turtle.left(90) 
   ```
1. What will be the output?
   ```python
   import turtle
   turtle.shape('turtle')
   turtle.setup(500, 500)
   turtle.penup()
   turtle.Screen().colormode(255)
   turtle.Screen.bgcolor(29,162,216)
   turtle.color(9,185,13)
   turtle.left(90)
   turtle.right(90)
   ```
1. What will be the output?
   ```python
   import turtle
   turtle.shape('turtle')
   turtle.setup(500, 500)
   turtle.penup()
   turtle.Screen().colormode(255)
   turtle.Screen.bgcolor(29,162,216)
   turtle.color(9,185,13)
   turtle.forward(200)
   turtle.left(90)
   turtle.forward(200)
   turtle.right(150)
   turtle.forward(300)
   turtle.forward(200)
   ```
1. What will be the output?
   ```python
   import turtule
   pen = turtle.Turtle()
   pen.color('blue')
   pen.pensize(5)
   pen.color("orange")
   pen.forward(100)
   pen.left(90)
   pen.forward(100)
   pen.left(90)
   pen.forward(100)
   pen.left(90)
   pen.forward(100)
   ```
1. What will be the output?
   ```python
   import turtule
   pen = turtle.Turtle()
   pen.color('blue')
   pen.pensize(5)
   pen.color("orange")
   pen.forward(100)
   pen.left(90)
   pen.forward(100)
   pen.left(90)
   pen.forward(100)
   pen.left(90)
   pen.forward(100)
   pen.hideturtle()
   ```
   
1. What will be the output?
   ```python
   import turtle
   pen = turtle.Turtle()
   pen.fillcolor('orange')
   pen.begin_fill()
   pen.circle(50)
   pen.end_fill()
   ```
1. What will be the output?
   ```python
   turtle_stamp = turtle.Turtle()
   turtle_stamp.shape('turtle')
   turtle_stamp.color('green')
   turtle_stamp.penup()
   turtle_stamp.forward(100)
   turtle_stamp.stamp()
   turtle_stamp.left(90)
   turtle_stamp.forward(100)
   turtle_stamp.stamp()
   turtle_stamp.left(90)
   turtle_stamp.forward(100)
   turtle_stamp.stamp()
   turtle_stamp.left(90)
   turtle_stamp.forward(100)
   turtle_stamp.stamp()
   ```
1. What will be the output?
   ```python
   import turtle
   import random
   stamp = turtle.Turtle()
   stamp.shape('turtle')
   stamp.penup()
   turtle.colormode(255)
   paces = 20
   random_red = 50
   random_green = 50
   random_blue = 50
   for i in range(50):
      random_red = random.radint(0,255)
      random_green = random.randint(0,255)
      random_blue = random.randiant(0,255)
      stamp.color(random_red,random_green,random_blue)
      stamp.stamp()
   paces += 3
   stamp.forward(paces)
   stamp.right(25)
   ```
1. Create a new file called fortune-teller, and save it. Within it, import the turtle module and random module. Create a new copy of the turtle object, and call it pointer; you can leave it as the default arrow shape because that's what we'll need ! Alse set its size. create another copy of the turtle object, and call it a *pen*. We'll use this to create our foutunr-teller board. Finally, create a variable to hold your spinner amount, and use the random module to pick a random number. Noe lift your pen so that it doesn't start drawing. We only want it to draw at the spots we tell it to. use goto function to move your pen to the four sides of your screen.

1. Using your knowledge of the **stamp()** function, create a program that stamps a turtle in each color of the ranbow. Make sure the turtles are in the same order sa the color of the rainbow !

1. Using the circle() function and yor knowledge of filling shaoes with colors, draw one big circle and fill it with a color. Then, draw a medium-sized circle and fill it with a different color. At this point make sure that you can still see the medium-sezed circle and wthat it's contained within the big circle. Finally, draw one small circle, fill it with a different color, and make sure it is contained within two larger circles

