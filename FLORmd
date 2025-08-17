import turtle

def draw_flower():
    screen = turtle.Screen()
    screen.bgcolor("white")
    screen.title("Flor con Turtle")

    flower = turtle.Turtle()
    flower.shape("turtle")
    flower.speed(10)
    flower.color("red", "yellow")

    flower.begin_fill()
    for _ in range(36):  # Dibuja los pétalos
        flower.circle(50, 60)
        flower.left(120)
        flower.circle(50, 60)
        flower.left(120)
        flower.right(10)
    flower.end_fill()

    flower.penup()
    flower.goto(0, -200)
    flower.pendown()
    flower.color("green")
    flower.setheading(90)
    flower.pensize(10)
    flower.forward(200)  # Tallo

    flower.hideturtle()
    screen.mainloop()

draw_flower()
