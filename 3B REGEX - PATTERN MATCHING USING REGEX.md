# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---

### AIM  
To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.

---

### PROGRAM

```python
import re
def match(x):
    pattern = r'^5'
    if re.match(pattern,x):
        print("True")
    else:
        print("False")
x = input()
match(x)
```
### OUTPUT
<img width="1181" height="235" alt="image" src="https://github.com/user-attachments/assets/c099d816-ff25-4c99-99b8-a02c780dec60" />

### RESULT
Therefore, the output is the example to write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.
