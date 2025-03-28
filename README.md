# Name: Muhammad Ahmad
# Roll No: 056

# 1) Write a for loop to print all even numbers from 2 to 20.
for num in range(2, 21, 2):
    print(num)

# 2) Create a list of names and use a for loop to print each name in uppercase.
names = ["Ali", "Sara", "Ahmed", "Zara"]
for name in names:
    print(name.upper())

# 3) Use a for loop with range() to print numbers from 10 to 1 in reverse order.
for num in range(10, 0, -1):
    print(num)

# 4) Iterate through a list of integers and print only the numbers that are divisible by 3.
numbers = [3, 7, 9, 12, 18, 22, 24]
for num in numbers:
    if num % 3 == 0:
        print(num)

# 5) Write a loop that prints the squares of numbers from 1 to 10.
for num in range(1, 11):
    print(num * num)

# 6) Given a list of temperatures in Celsius, use a for loop to convert each to Fahrenheit.
temperatures_celsius = [0, 10, 20, 30, 40]
for temp in temperatures_celsius:
    fahrenheit = (temp * 9/5) + 32
    print(fahrenheit)

# 7) Create a for loop that prints the multiplication table of 5.
for num in range(1, 11):
    print(f"5 x {num} = {5 * num}")

# 8) Write a program to find the sum of all numbers in a list using a for loop.
numbers = [2, 4, 6, 8, 10]
sum_numbers = 0
for num in numbers:
    sum_numbers += num
print(sum_numbers)

# 9) Use a for loop to iterate through a string and print each character separately.
text = "Python"
for char in text:
    print(char)

# 10) Create a list of words and use a for loop to print only the words with more than 5 letters.
words = ["apple", "banana", "cat", "elephant", "dog", "giraffe"]
for word in words:
    if len(word) > 5:
        print(word)
