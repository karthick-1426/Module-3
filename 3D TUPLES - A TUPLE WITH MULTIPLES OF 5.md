# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 3

---

### AIM  
To write a Python program to create a tuple containing all multiples of 3 up to a given number **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_3` with values starting from `3` up to `N - 1`, stepping by `3`.  
4. Return the tuple `multiples_of_3`.  
5. Print the resulting tuple.  
6. Terminate the program.

---

### PROGRAM

```python
n=int(input())
t=tuple([i for i in range(3,n,3)])
print(t)
print("Sum is",sum(t))
```

### OUTPUT
<img width="1189" height="279" alt="image" src="https://github.com/user-attachments/assets/0508c19a-7d69-4030-b202-51732b8dd7e4" />

### RESULT
Therefore, the output is the example to write a Python program to create a tuple containing all multiples of 3 up to a given number **N**.
