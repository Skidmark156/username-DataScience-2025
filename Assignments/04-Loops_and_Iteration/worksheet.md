# 📝 Worksheet: 04 - Loops and Iteration

Practice and reflect on how loops work in Python.

---

## 🔁 Section 1: For Loops

1. What does `range(5)` produce?

`Answer:` 0, 1, 2, 3, 4
2. Write a `for` loop that prints numbers 1 to 10, but skips 5.

```python
for i in range(1, 11):
    if i == 5:
        continue
    print(i)
```

---

## 🔁 Section 2: While Loops

3. What’s the difference between a `for` loop and a `while` loop?

`Answer:` A for loop runs a fixed number of times (over a range, list, etc.). A while loop runs as long as its condition is True.

4. What happens if a `while` loop's condition never becomes `False`?

`Answer:` It creates an infinite loop, which keeps running forever (until stopped manually).

---

### ✏️ Task: Countdown with While

```python
count = 5
while count > 0:
    print(count)
    count -= 1
```

---

## 📁 Section 3: File Reading and `with`

5. What does the `with` statement do when opening a file?

`Answer:`It automatically opens and closes the file safely, even if errors occur.

6. How do you loop over each line in a file?

`Answer:` with open("data.txt", "r") as f:
    for line in f:
        print(line)
        
---

### ✏️ Task: File Filter

Write code that prints only the lines in a file that contain the word `"error"`.

```python
with open("data.txt", "r") as f:
    for line in f:
        print(line)
```
