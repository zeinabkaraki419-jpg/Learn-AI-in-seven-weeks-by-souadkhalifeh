# Learn-AI-in-seven-weeks-by-souadkhalifeh
​"Daily coding updates, notes, and projects tracking my 7-week roadmap to becoming an AI Expert."
# 🚀 My AI & Python Learning Journey

Welcome to my repository where I document my daily progress in mastering Python and Artificial Intelligence!

---

## 📅 Week 1: Python Fundamentals

### 🔹 Day 1: Variables & Data Types
* **Concept Learned:** How to store information in memory using variables and understanding basic data types (`str`, `int`, `float`, `bool`).
* **Code Implementation:**
    ```python
    # Storing different types of data
    name = "Alice"       # String (str)
    age = 25             # Integer (int)
    height = 1.68        # Float (float)
    is_student = True    # Boolean (bool)

    # Printing the values
    print("Name:", name)
    print("Age:", age)
    ```

---

### 🔹 Day 2: Conditions (if / elif / else)
* **Concept Learned:** Making programs make smart decisions based on conditions and maintaining correct code indentation.
* **Code Implementation:**
    ```python
    # Requesting age from the user and classifying it
    age = int(input("What's your age? "))

    if age < 18:
        print("You are a minor.")
    elif age >= 18 and age <= 64:
        print("You are an adult.")
    else:
        print("You are a senior.")
    ```

---

### 🔹 Day 3: Loops in Python (for & while)

Today, I mastered how to automate repetitive tasks using Loops in Python. I learned how to let the computer do the heavy lifting using just a few lines of code.

#### 💡 Key Concepts Learned:
- **`for` Loop:** Used when the number of iterations is known in advance (e.g., using `range()`).
- **`while` Loop:** Used to repeat code as long as a specific condition remains `True`.
- **`if-else` inside Loops:** Combined conditional logic with loops to handle even numbers and print empty lines for odd numbers.

#### 🛠️ Code Practice:
```python
# A program that loops from 1 to 10, prints even numbers, and leaves a blank line for odd numbers
for number in range(1, 11):
    if number % 2 == 0:
        print(f"number is even {number}")
    else:
        print("")
    ```

---

### 🔹 Day 3: Loops in Python (for & while)

Today, I mastered how to automate repetitive tasks using Loops in Python. I learned how to let the computer do the heavy lifting using just a few lines of code.

#### 💡 Key Concepts Learned:
- **`for` Loop:** Used when the number of iterations is known in advance (e.g., using `range()`).
- **`while` Loop:** Used to repeat code as long as a specific condition remains `True`.
- **Indentation:** Remembering that the code block inside the loop must be indented.

#### 🛠️ Code Practice:
```python
# Example of a for loop printing numbers from 1 to 5
for i in range(1, 6):
    print(f"Iteration number: {i}")
  ```

---

### 🔹 Day 4: Functions 
- **Concept:** Learning how to bundle pieces of code into reusable blocks using functions (`def`).
- **Key Takeaways:** - Functions help avoid code repetition (DRY Principle).
  - Understanding inputs (`parameters`) and outputs (`return`).

#### 💻 Code Challenge (Day 4):
```python
def calculate_average(grade1, grade2):
    average = (grade1 + grade2) / 2
    return average
final_result = calculate_average(85, 95)
print(f"The calculated average is: {final_result}")
```

---

## 🗂️ Week 1 - Day 5: Solving Programming Challenges

Today, I applied the core programming concepts I learned throughout this week (Variables, Conditions, and Loops) by solving two practical Python challenges:

### 1️⃣ Challenge 1: Simple Calculator
An interactive program that asks the user to input two numbers and choose a mathematical operation. It processes the data using conditions and includes edge-case handling to prevent division by zero.

**Concepts Used:**
- User input handling with `input()`.
- Data type conversion using `float()`.
- Conditional logic with `if`, `elif`, and `else`.

---

### 2️⃣ Challenge 2: Filtering Even Numbers
A loop script that iterates through numbers from 1 to 50 and filters out only the even numbers.

**Concepts Used:**
- Loops using `for loop` and the `range()` function.
- Checking divisibility using the Modulo operator `%`.

---

# ==========================================
# Challenge 1: Simple Calculator
# ==========================================

print("--- Challenge 1: Simple Calculator ---")

# Request two numbers from the user and convert them to float to allow decimals
num1 = float(input("Please enter the first number: "))
num2 = float(input("Please enter the second number: "))

# Request the mathematical operation
operation = input("Choose an operation (+, -, *, /): ")

# Conditional statements to execute the chosen operation
if operation == "+":
    result = num1 + num2
    print(f"Result: {num1} + {num2} = {result}")
elif operation == "-":
    result = num1 - num2
    print(f"Result: {num1} - {num2} = {result}")
elif operation == "*":
    result = num1 * num2
    print(f"Result: {num1} * {num2} = {result}")
elif operation == "/":
    # Smart validation to prevent division by zero
    if num2 != 0:
        result = num1 / num2
        print(f"Result: {num1} / {num2} = {result}")
    else:
        print("Error: Division by zero is not allowed!")
else:
    print("Invalid operation symbol! Please enter one of (+, -, *, /)")


# ==========================================
# Challenge 2: Filtering Even Numbers
# ==========================================

print("\n--- Challenge 2: Filtering Even Numbers from 1 to 50 ---")

# A loop iterating through numbers from 1 to 50
for number in range(1, 51):
    # Check if the number is even (remainder of division by 2 is zero)
    if number % 2 == 0:
        print(number)

```

---
## 🎓 Day 5: Weekly Project - Student Grade System

### 📝 Project Description
A comprehensive Python script that captures a student's name and grades across three subjects. It utilizes a custom function to calculate the average score and applies conditional logic to determine if the student passed or failed.

### 💻 Code Implementation
```python
student_name = input("enter your name please ")
math_grade = int(input("enter your Math grade: "))
physics_grade = int(input("enter your Physics grade: "))
history_grade = int(input("enter your History grade: "))

def calculate_average(grade1, grade2, grade3):
    average = (grade1 + grade2 + grade3) / 3
    return average

final_result = calculate_average(math_grade, physics_grade, history_grade)
print(f"The calculated average is: {final_result:.2f}")

if final_result >= 50:
     print(f"Congratulations {student_name}! Your result: Pass 🎉")
else:
   print(f"I am sorry {student_name}, you failed. Your result: Fail ❌")
## 🎓 Day 5: Weekly Project - Student Grade System

### 📝 Project Description
A comprehensive Python script that captures a student's name and grades across three subjects. It utilizes a custom function to calculate the average score and applies conditional logic to determine if the student passed or failed.

### 💻 Code Implementation
```python
student_name = input("enter your name please ")
math_grade = int(input("enter your Math grade: "))
physics_grade = int(input("enter your Physics grade: "))
history_grade = int(input("enter your History grade: "))

def calculate_average(grade1, grade2, grade3):
    average = (grade1 + grade2 + grade3) / 3
    return average

final_result = calculate_average(math_grade, physics_grade, history_grade)
print(f"The calculated average is: {final_result:.2f}")

if final_result >= 50:
     print(f"Congratulations {student_name}! Your result: Pass 🎉")
else:
   print(f"I am sorry {student_name}, you failed. Your result: Fail ❌")
```

---
