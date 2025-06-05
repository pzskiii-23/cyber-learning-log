# Python Day 2 Recap

```python
def port_checker(port):
    if port == 22:
        return "That's the SSH port!"
    elif port == 80:
        return "That's the HTTP port!"
    else:
        return f"Cool, that's port {port}"

name = input("What is your name? ")
port = int(input("What is your port? "))

print(f"Hello, {name}!")
print(port_checker(port))
```

**What I learned:**
- How to collect user input (`input()`).
- How to use `def` to create functions.
- How to use `if/elif/else` for logic and returning values.
- How to print dynamic messages and use function arguments.

**What was easy:**
- Writing and calling functions.
- Using print and input for basic interactivity.

**What was tricky:**
- Remembering to convert input to integer.
- Keeping the indentation correct in Python blocks.

**What I want to do next:**
- Write more advanced functions.
- Try automating basic IT/cyber tasks using Python.
- Use lists and loops for more complex data handling.
