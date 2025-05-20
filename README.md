# 100-Patterns-Printing-using-Python
# Pattern Printing in Python

This README showcases various pattern programs with `n = 5`.

## 📌 Pattern 1: Square of Asterisks

**Code:**
```python
n = 5
for i in range(1, n+1):
    print(n * "* ")
```

**Output:**
```
* * * * * 
* * * * * 
* * * * * 
* * * * * 
* * * * * 
```
---

## 📌 Pattern 2: Rows with Increasing Numbers

**Code:**
```python
n = 5
for i in range(1, n+1):
    print(n * (str(i) + " "))
```

**Output:**
```
1 1 1 1 1 
2 2 2 2 2 
3 3 3 3 3 
4 4 4 4 4 
5 5 5 5 5 
```
---

## 📌 Pattern 3: Sequential Numbers in Grid

**Code:**
```python
n = 5
for i in range(1, n+1):
    for j in range(1, n+1):
        print(j, end=" ")
    print()
```

**Output:**
```
1 2 3 4 5
1 2 3 4 5
1 2 3 4 5
1 2 3 4 5
1 2 3 4 5
```
---

## 📌 Pattern 4: Repeating Alphabets

**Code:**
```python
n = 5
l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
for j in l[0:n]:
    print(n * (str(j) + " "))
```

**Output:**
```
A A A A A 
B B B B B 
C C C C C 
D D D D D 
E E E E E 
```
---

## 📌 Pattern 5: Right Angle Triangle with Asterisks

**Code:**
```python
n = 5
for i in range(1, n+1):
    print("* " * i)
```

**Output:**
```
* 
* * 
* * * 
* * * * 
* * * * * 
```
---

## 📌 Pattern 6: Number Triangle

**Code:**
```python
n = 5
for i in range(1, n+1):
    for j in range(1, i+1):
        print(j, end=" ")
    print()
```

**Output:**
```
1
1 2
1 2 3
1 2 3 4
1 2 3 4 5
```
---

## 📌 Pattern 7: Inverted Number Triangle

**Code:**
```python
n = 5
for i in range(n, 0, -1):
    for j in range(1, i+1):
        print(j, end=" ")
    print()
```

**Output:**
```
1 2 3 4 5
1 2 3 4
1 2 3
1 2
1
```

---
