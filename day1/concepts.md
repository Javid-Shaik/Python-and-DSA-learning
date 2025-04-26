
# Python Day 1 - Concepts: Variables, Conditions, Loops

---

## 1. Variables

A **variable** is like a labeled box where you can store data in Python.

- **Python is dynamically typed**, meaning you don't need to declare the type of a variable.
- You can simply assign a value, and Python figures out the type automatically.

```python
# Example
age = 25
name = "Alice"
pi = 3.14159
is_student = True
```

### Rules for Variable Naming:
- Must start with a letter (a-z, A-Z) or an underscore (_).
- Cannot start with a number.
- Can contain letters, digits, and underscores.
- Case-sensitive (`name` and `Name` are different).

### Special Concepts:
- **Multiple Assignment**: Assign multiple variables at once.
  ```python
  a, b, c = 1, 2, 3
  ```

- **Swapping Variables**:
  ```python
  x, y = 5, 10
  x, y = y, x
  ```

- **Mutable vs Immutable Types**:
  - **Immutable**: int, float, string, tuple → Cannot be changed after creation.
  - **Mutable**: list, dict, set → Can be changed.

---

## 2. Conditions (If-Else)

Conditions let you **control the flow** of your code.

### Basic If-Else:

```python
x = 10
if x > 5:
    print("Greater than 5")
else:
    print("5 or smaller")
```

### Elif (Else If):

```python
score = 85
if score >= 90:
    print("Grade A")
elif score >= 80:
    print("Grade B")
else:
    print("Grade C")
```

### Important Points:
- Indentation is **mandatory** (usually 4 spaces).
- `if` can work with any **truthy** or **falsy** value.
  - **Falsy values**: `False`, `None`, `0`, `''`, `[]`, `{}`, `()`
  - Everything else is **truthy**.

### Logical Operators:
| Operator | Example | Meaning |
|:---|:---|:---|
| `and` | `a > 0 and b > 0` | True if both are True |
| `or` | `a > 0 or b > 0` | True if any one is True |
| `not` | `not (a > 0)` | True if expression is False |

---

## 3. Loops

Loops let you **repeat actions** multiple times.

---

### For Loop:

```python
for i in range(5):
    print(i)
```

- `range(5)` generates numbers from 0 to 4.
- Can be used to iterate over lists, strings, tuples.

```python
for char in "Python":
    print(char)
```

---

### While Loop:

```python
n = 5
while n > 0:
    print(n)
    n -= 1
```

- Runs as long as the condition is True.

**Be careful!**  
If the condition never becomes False, the loop will run forever (infinite loop).

---

### Special Keywords:
- `break` → Exit the loop immediately.
- `continue` → Skip the rest of the current iteration and go to the next.

Example with `break`:

```python
for num in range(10):
    if num == 5:
        break
    print(num)
```

Example with `continue`:

```python
for num in range(5):
    if num == 2:
        continue
    print(num)
```

---

## 4. Mini-Experiments To Try

Try these to **explore**:

- Assign a string to a variable, then assign a number to the same variable.
- Nest if-else inside another if-else.
- Try `if ""` or `if 0` and see if it runs the block.
- Create a for loop that goes backwards (e.g., `range(5, 0, -1)`).
- Make a while loop that stops only when the user types "exit".

---

## 5. Common Errors and How to Avoid Them

| Mistake | Example | Why It Happens |
|:---|:---|:---|
| Forgetting Indentation | `if x > 5: print(x)` | Python uses indentation to define blocks. |
| Comparing different types | `5 > "5"` | You can't compare int and str directly. |
| Infinite while loop | `while True: pass` | Always ensure the condition can become False. |
| Wrong variable names | `2name = "abc"` | Variable names can't start with numbers. |

---

## 6. Best Learning Resources

Only the **best**, not overwhelming:

- [Python Official Tutorial (Easy Part)](https://docs.python.org/3/tutorial/introduction.html)
- [W3Schools Python Basics](https://www.w3schools.com/python/python_intro.asp) — very beginner-friendly.
- [Programiz Python Basics](https://www.programiz.com/python-programming) — clear explanations with examples.

(You only need these three for now. **Do not** search too much and get confused.)

---

# Summary

Today you learned:

- How to create and use **variables**.
- How to control your code using **if-else** statements.
- How to repeat actions using **for loops** and **while loops**.
- How to **experiment** with the Python syntax.


>**Tip:** Practice small experiments after reading each part. Don't try to memorize — **try to play**.

---
