# Foundational Concepts

## 1.1 Variables

A variable is like a labeled box where you store data. In programming, it’s a way to give a name to a value so you can use it later.

### Explanation
Variables hold different types of data, like numbers, text, or lists. In Python, you don’t need to declare the type explicitly—it figures it out for you.

### Code Snippet
```python
name = "Alice"  # String variable
age = 25        # Integer variable
height = 5.6    # Float variable
print(name, age, height)
```

---

## 1.2 Arrays (Lists in Python)

An array is a collection of items stored in a single variable. In Python, we use lists instead of traditional arrays.

### Explanation
Lists store multiple values in order. You can access items by their position (index), starting at 0.

### Code Snippet
```python
groceries = ["apples", "bananas", "milk"]
print(groceries[0])  # Outputs: apples
groceries.append("bread")  # Adds "bread" to the end
print(groceries)  # Outputs: ['apples', 'bananas', 'milk', 'bread']
```

---

## 1.3 Basic Programming Logic

Programming logic involves controlling the flow of your code using conditions and loops.

### Conditionals (if-else)
Make decisions based on conditions.

#### Code Snippet
```python
weather = "rainy"
if weather == "rainy":
    print("Take an umbrella")
else:
    print("Wear sunglasses")
```

### Loops (for/while)
Repeat actions.

#### Code Snippet
```python
groceries = ["apples", "bananas", "milk"]
for item in groceries:
    print(f"Adding {item} to cart")
```
