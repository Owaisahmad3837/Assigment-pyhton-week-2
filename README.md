i do all this but i need to look better so take help from chatgpt make better formet Like Question then Answer:


# Python Assignment – Week 2
**Subject:** Python Programming
**Name:** Owais Ahmad
**Father’s Name:** Siraj Gul
**Department:** Computer Science
**Semester:** 4th (Software)

---

## Part A: Loops

### Q1. Print numbers from 1 to 10 using a for loop.

```python
for i in range(1, 11):
    print(i)
```

---

### Q2. Print even numbers from 2 to 20 using a for loop.

```python
for i in range(2, 21):
    if i % 2 == 0:
        print(i)
```

---

### Q3. Print all characters of the string "Python" using a loop.

**Using for loop**

```python
char = "Python"
for i in char:
    print(i)
```

**Using while loop**

```python
char = "Python"
i = 0
while i < len(char):
    print(char[i])
    i += 1
```

---

### Q4. Print numbers from 5 to 1 using a loop.

```python
for i in range(5, 0, -1):
    print(i)
```

---

### Q5. Use a while loop to print numbers from 1 to 5.

```python
n = 1
while n <= 5:
    print(n)
    n += 1
```

---

## Part B: Functions 

### Q6. Create a function that prints "Hello Python" when called.

```python
def hi():
    print("Hello Python")

hi()
```

---

### Q7. Create a function that takes one number and prints it.

```python
def show_number():
    n = int(input("Enter number: "))
    print(n)

show_number()
```

---

### Q8. Create a function that takes two numbers and prints their sum.

```python
def add(a, b):
    print(a + b)

add(2, 2)
```

---

### Q9. Create a function that takes one number and checks whether it is even or odd.

```python
def check(n):
    if n % 2 == 0:
        print("Even")
    else:
        print("Odd")

check(10)
```

---

### Q10. Create a function that prints numbers from 1 to 5 using a loop.

```python
def print_numbers():
    for i in range(1, 6):
        print(i)

print_numbers()
```

---

## Mini Project

### Project Title: Number Table Generator

### Task

* Create a function that takes one number as input
* Use a loop inside the function
* Print the table of that number (from 1 to 10)
* Use only loops and functions

---

### Solution

```python
def table():
    n = int(input("Enter number: "))
    t = 1
    while t <= 10:
        print(f"{n} x {t} = {n * t}")
        t += 1

table()
```
