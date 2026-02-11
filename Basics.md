
Taking input

Type casting

Adding numbers

Printing formats

Multiple inputs using map() and split()

Swapping variables



---

🐍 Python Basic Input & Output – Simple Notes


---

1️⃣ Taking Input from User (String)

By default, input() always takes data as string.

✅ Example:

name = input("Enter your name: ")
print(name)

🔎 Explanation:

input() takes user input.

The value is stored in variable name.

print() displays the value.



---

2️⃣ Taking Integer Input

Since input() gives string, we convert it using int().

✅ Example:

a = int(input("Enter a: "))
b = int(input("Enter b: "))
print(a + b)

🔎 Explanation:

int() converts string to integer.

Now we can perform addition.



---

3️⃣ Checking Type of Variable

Use type() to check data type.

✅ Example:

a = 23.4
print(type(a))

🖥 Output:

<class 'float'>


---

4️⃣ Multiple Input in One Line (Using split & map)

If user enters numbers separated by comma:

✅ Example:

a, b, c = map(int, input("Enter numbers separated by comma: ").split(","))
print(a, b, c, sep=",")

🧠 How it Works:

input() → takes full string (example: 100,200,300)

.split(",") → splits into list: ['100', '200', '300']

map(int, ...) → converts each value into integer

Values stored in a, b, c



---

5️⃣ Different Ways to Print Variables

Assume:

a = 10
b = 20
c = 30


---

✅ Method 1: Old Style (% formatting)

print("%d %d %d" % (a, b, c))

Output:

10 20 30


---

✅ Method 2: format() method

print("{},{},{}".format(a, b, c))

Output:

10,20,30


---

✅ Method 3: f-string (Best & Modern Way)

print(f"{a}, {b}, {c}")

Output:

10, 20, 30

⭐ Recommended: Use f-strings


---

6️⃣ Print with Custom Separator

print(a, b, sep="\n")

Output:

10
20

sep → separator between values

end → what to print at end


Example:

print(a, b, sep="\n", end="--\n")


---

7️⃣ Swapping Two Variables

✅ Without Temporary Variable

a = 10
b = 20

print(f"Before swap: a = {a}, b = {b}")

a, b = b, a

print(f"After swap: a = {a}, b = {b}")

🖥 Output:

Before swap: a = 10, b = 20
After swap: a = 20, b = 10

💡 Python allows direct swapping like this.


---

🔑 Important Functions Summary

Function	Purpose

input()	Takes input from user
int()	Converts to integer
float()	Converts to decimal
type()	Checks data type
split()	Splits string
map()	Applies function to multiple values
print()	Displays output



---

🎯 Small Practice Program (Complete Example)

# Taking name
name = input("Enter your name: ")
print("Hello", name)

# Adding numbers
a = int(input("Enter a: "))
b = int(input("Enter b: "))
print("Sum:", a + b)

# Multiple input
x, y = map(int, input("Enter two numbers (x,y): ").split(","))
print("First:", x)
print("Second:", y)

# Swapping
x, y = y, x
print("After swap:", x, y)


-
