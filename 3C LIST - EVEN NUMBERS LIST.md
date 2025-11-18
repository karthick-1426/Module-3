# Exp.No:3c
## LIST - EVEN NUMBERS LIST

---

### AIM  
To write a Python function that accepts a number **N** and creates a list containing all values divisible by 7 up to **N**.

---

### ALGORITHM

1. Begin the program.
2. Define a function named find_divisible_by_7 that accepts one integer parameter: N.
3. Initialize an empty list called divisible_numbers to store the results.
4. Input Validation (Optional but Recommended): Check if N is a positive integer. If not, inform the user or return an empty list.
5. Start a loop to iterate through every number (current_number) starting from 1 up to and including N.
6. Inside the loop, check the condition for divisibility by 7 using the modulo operator: if current_number % 7 == 0.
7. If the condition is true (the remainder is 0), append the current_number to the divisible_numbers list.
8. After the loop completes, return the divisible_numbers list.
9. (Demonstration) Call the function with one or more example numbers for N (e.g., 50, 100).
10. (Demonstration) Print the list returned by the function for each test case.
11. Terminate the program.

---

### PROGRAM

```python
n=eval(input())
l=len(n)
i=0
while i<l:
    if n[i]%7==0:
        n[i],n[i+1]=n[i+1],n[i]
        i+=2
    else:
        i+=1
print(n)
```

### OUTPUT
<img width="1186" height="238" alt="image" src="https://github.com/user-attachments/assets/01884d0d-1480-4f49-92fc-fa2375a0fd39" />

### RESULT
Therefore, the output is the example to write a Python function that accepts a number **N** and creates a list containing all values divisible by 7 up to **N**.
