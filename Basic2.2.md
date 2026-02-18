

1️⃣ Multiple Comparison

✅ Code

a = 10
b = 10
c = 10
d = 10

e = a == b == c == d
print(e)

🔎 Explanation

a = 10 → Assigns value 10 to variable a

== → Comparison operator (checks equality)

a == b == c == d → Checks if all variables are equal

e = ... → Stores result (True or False) in variable e

print(e) → Displays the result


📌 Output

True


---

2️⃣ Logical AND Condition

✅ Code

a = 10
b = 10
c = 5

print(a == b and c == b)

🔎 Explanation

and → Logical operator
Returns True only if both conditions are True


Conditions:

a == b → True (10 == 10)

c == b → False (5 != 10)


Since one condition is False:

📌 Output

False


---

3️⃣ Check Positive or Negative Number

✅ Code

num = int(input("Enter the number: "))

if num > 0:
    print("Positive")
else:
    print("Negative")

🔎 Explanation

input() → Takes user input

int() → Converts input string to integer

if → Condition checking statement

num > 0 → Checks if number is greater than zero

else → Executes when if condition is False


📌 Example

Input:

4

Output:

Positive


---

4️⃣ Check Even or Odd Number

✅ Code

num = int(input("Enter the number: "))

if num % 2 == 0:
    print("Even")
else:
    print("Odd")

🔎 Explanation

% → Modulus operator (gives remainder)

num % 2 == 0 → If remainder is 0 → number is Even

Otherwise → Odd


📌 Example

Input:

4

Output:

Even


---

5️⃣ Find Greatest Among Three Numbers (Using Separate Inputs)

✅ Code

a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))

if a > b and a > c:
    print(a)
elif b > a and b > c:
    print(b)
else:
    print(c)

🔎 Explanation

and → Both conditions must be True

elif → Else if (checks another condition)

Compares all three numbers

Prints the greatest number



---

6️⃣ Find Greatest (Using Single Line Input)

✅ Code

a, b, c = map(int, input("Enter numbers separated by comma: ").split(","))

if a > b and a > c:
    print(a)
elif b > a and b > c:
    print(b)
else:
    print(c)

🔎 Explanation

input() → Takes input as string

.split(",") → Splits input by comma

map(int, ...) → Converts each value to integer

a, b, c = → Assigns values to variables


Example input:

4,5,6

Output:

6


---

7️⃣ Using Ternary Operator (Short Method)

✅ Code

a, b, c = map(int, input("Enter numbers separated by comma: ").split(","))

print("a is greatest") if a > b and a > c else \
print("b is greatest") if b > a and b > c else \
print("c is greatest")

🔎 Explanation

condition if true else false → Ternary operator

Short way to write if-elif-else

Checks conditions in one line



---

8️⃣ Simple Arithmetic Example from Your Screenshot

✅ Code

a, b = map(int, input("Enter two numbers separated by comma: ").split(","))

print(a + b)
print(a - b)
print(a * b)
print(a / b)

🔎 Explanation

+ → Addition

- → Subtraction

* → Multiplication

/ → Division



---

🔥 Important Concepts Summary

Symbol	Meaning

=	Assignment
==	Equal comparison
>	Greater than
%	Modulus (remainder)
and	Logical AND
if	Condition statement
elif	Else if
else	Otherwise
map()	Apply function to multiple values
split()	Break string into parts


