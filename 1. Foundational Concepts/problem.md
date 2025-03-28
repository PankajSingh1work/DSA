# Practice Problems

## Problem 1: Favorite Movie Details
**Task:**  
Create variables for your favorite movie, its release year, and your rating (out of 10). Print them.

**Solution:**
```python
movie_name = "Awarapan"
release_year = 2007
rating = 7.4
print(movie_name, release_year, rating)
```

---

## Problem 2: Friends List
**Task:**  
Create a list of 5 friends’ names. Print the second name and add a new friend to the list.

**Solution:**
```python
friends = ["Ashutosh", "Amit", "Rahul", "Divyanshu", "Navneet"]
print(friends[1])
friends.append("Pankaj")
print(friends)
```

---

## Problem 3: Even or Odd & Looping Numbers
**Task:**  
Write a program that checks if a number is even or odd. Then, print all numbers from 1 to 10 using a loop.

**Solution:**
```python
input_number = int(input("Enter a number: "))
if input_number % 2 == 0:
    print("Even")
else:
    print("Odd")

for num in range(1, 11):
    print(num)
```




