# Happy Holi Turtle Graphics

This is a simple Python project that uses the Turtle graphics library to display a "Happy Holi" text. The project is perfect for beginners who want to learn how to use the Turtle graphics library in Python.

## Snapshots
![Screenshot 2024-06-23 160657](https://github.com/laxman-rathod/Python-Turtle/assets/131651450/bfc0752d-b773-4d08-9609-2f5b03f7d68a)

## Features

- Displays "Happy Holi" text on the screen using Turtle graphics
- Simple and easy-to-understand code
- Suitable for beginners

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed Python 3.x on your machine.
- You have installed the Turtle graphics library. If not, you can install it using the following command:

```bash
pip install PythonTurtle
```

## Installation

**To install this project, follow these steps:**

1. Clone the repository to your local machine:
  ```bash
git clone https://github.com/laxman-rathod/Python-Turtle.git
```

2. Navigate to the project directory:
```bash
cd happy-holi-turtle-graphics
```

## Usage
**To run the project, execute the following command:**
```bash
python happy_holi.py
```

You should see a window displaying "Happy Holi" text created using Turtle graphics.

## Code Explanation

**Here's a brief explanation of the code:**

```bash
import turtle

# Set up the screen
screen = turtle.Screen()
screen.title("Happy Holi")
screen.bgcolor("white")

# Create a turtle object
pen = turtle.Turtle()
pen.color("blue")
pen.hideturtle()
pen.speed(2)

# Function to display "Happy Holi"
def write_happy_holi():
    pen.penup()
    pen.goto(0, 0)
    pen.pendown()
    pen.write("Happy Holi", align="center", font=("Arial", 40, "bold"))

# Display the text
write_happy_holi()

# Keep the window open
turtle.done()
```

## Contributing
If you want to contribute to this project, follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit them (git commit -m 'Add some feature').
Push to the branch (git push origin feature-branch).
Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE). 
