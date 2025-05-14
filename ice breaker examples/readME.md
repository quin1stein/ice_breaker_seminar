# Ice Breaker: Python Guessing Games

Welcome to our ice breaker activity! Let's test your Python instincts with a few simple but tricky challenges.
Can you **guess the error** or **guess the output** correctly?

---

## Guess the Error (Moderate Easy)

### Error #1

```python
def greet(name):
    print("Hello" + name)

greet()
```

**Question:** This function is supposed to greet someone by name. But when we run it, something goes wrong. What’s the error?

> **Answer:** `TypeError` – greet() is missing 1 required positional argument: 'name'.

**Fix:**

```python
greet("Dallen")
```

---

### Error #2

```python
x = [1, 2, 3]
print(x[3])
```

**Question:** This code tries to print an item from a list. What do you think will happen?

> **Answer:** `IndexError` – List index out of range.

**Explanation:** Valid indices for `x = [1, 2, 3]` are `0, 1, 2`.

---

## Guess the Output (Moderate Easy)

### Output #1

```python
def mystery(num):
    return num * num

print(mystery(2) + mystery(3))
```

**Question:** This function multiplies a number by itself. What will be printed when we run this code?

> **Answer:** `13`

**Explanation:** `mystery(2)` = 4, `mystery(3)` = 9 → 4 + 9 = 13

---

### 🧠 Output #2

```python
x = True
y = False
print(x + y)
```

**Question:** What will this code print? Remember, this isn’t just a logic question—it’s also about how Python treats booleans.

> **Answer:** `1`

**Explanation:** In Python, `True` is `1`, and `False` is `0` → `True + False = 1 + 0 = 1`

---
