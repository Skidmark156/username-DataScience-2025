# 📝 Worksheet: 03 - Scalar Types and Control Flow

Use this worksheet to reinforce your understanding of variables, comparisons, and decision logic.

---

## 🧠 Section 1: Scalar Types

1. What is the output of the following code?

```python
x = 10
print(type(x))
```

`Answer:`<class 'int'>

2. What scalar type would best represent:
   - A person's name: str
   - Their age: int
   - Whether they passed a test: bool

---

### ✏️ Task: Type Practice

```python
# Examples of scalar types
age = 21
pi = 3.14
name = "Milagro"
passed = True

print(age, type(age))
print(pi, type(pi))
print(name, type(name))
print(passed, type(passed))

```

---

## 🔁 Section 2: Comparison Operators

3. What does the `!=` operator mean?

`Answer:` Not equal to

4. What will the following code print?

```python
a = 5
b = 3
print(a < b or b < 10)
```

`Answer:`  True

---

## 🔀 Section 3: Control Flow

5. Write a conditional that prints "Pass" if a grade is >= 70, and "Fail" otherwise.

```python
grade = int(input("Enter your grade: "))

if grade >= 70:
    print("Pass")
else:
    print("Fail")

```

6. What does `elif` allow you to do?

`Answer:` Check multiple conditions in sequence after an if without starting a new if-block.

---

### ✏️ Task: Your Turn

weather = input("What is the weather today? ")

if weather.lower() == "sunny":
    print("Bring sunscreen")
elif weather.lower() == "raining":
    print("Take an umbrella")
else:
    print("Check the forecast")

