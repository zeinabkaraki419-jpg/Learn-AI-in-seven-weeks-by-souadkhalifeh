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
