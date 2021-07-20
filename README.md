import turtle

col =('red','green','yellow','purple','white')
t = turtle.Turtle()
screen =turtle.Screen()
screen.bgcolor('black')
t.speed(100)

for i in range (200):
    t.color(col[i%5])
    t.forward(i*6)
    t.left(150)
    t.width(2)
