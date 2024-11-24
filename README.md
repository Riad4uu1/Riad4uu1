-# Import the turtle library for drawing
import turtle

# Set up the screen
screen = turtle.Screen()
screen.setup(width=800, height=600)
screen.bgcolor("black")
screen.title("Heart of Love")

# Create a turtle object for drawing
pen = turtle.Turtle()
pen.shape("turtle")
pen.speed(2)
pen.width(3)

# Function to draw a heart shape
def draw_heart():
    pen.color("red")
    pen.begin_fill()
    pen.left(50)
    pen.forward(133)
    pen.circle(50, 200)
    pen.right(140)
    pen.circle(50, 200)
    pen.forward(133)
    pen.end_fill()

# Function to display the "Love" text
def display_message():
    pen.penup()
    pen.goto(-70, -70)
    pen.color("white")
    pen.write("can you be my mine ", align="center", font=("Arial", 24, "bold"))
    pen.goto(-70, -100)
    pen.write("i love you <3", align="center", font=("Arial", 18, "italic"))

# Main drawing function
def main():
    pen.penup()
    pen.goto(0, 0)
    pen.pendown()
    draw_heart()
    display_message()

# Run the main function
main()

# Keep the window open until the user closes it
turtle.done() 👋 Hi, I’m @Riad4uu1
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Riad4uu1/Riad4uu1 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
