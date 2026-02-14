



---

📘 COMPLETE PYTHON BASIC NOTES (From Your Images)


---

1️⃣ Division in Python

🔹 1. Normal Division / (Float Result)

It gives answer in decimal.

a = 8
b = 5
c = a / b
print("Float", c)

✅ Output:

Float 1.6


---

🔹 2. Floor Division // (Integer Result)

Removes decimal part.

a = 8
b = 5
c = a // b
print("Integer", c)

✅ Output:

Integer 1


---

🔹 More Examples

a = 10
b = 5
print(a / b)   # 2.0
print(a // b)  # 2

a = 10
b = 5.5
print(a / b)

Output:

1.8181818181818181


---

2️⃣ Taking Input from User

a = int(input("Enter the number: "))
print(a)

🔹 Explanation:

input() → Takes value from user (as string)

int() → Converts string to integer

print() → Displays output



---

3️⃣ If-Else Condition

🔹 Check Adult

age = int(input("Enter the number: "))

if age >= 18:
    print("You are adult")
else:
    print("Not adult")

Explanation:

If condition is true → first block runs
If false → else block runs


---

🔹 Voting Eligibility

age = int(input("Enter the number: "))

if age >= 18:
    print("Eligible for Vote")
else:
    print("Not eligible for vote")


---

4️⃣ For Loop

Used to repeat code multiple times.

🔹 Print Numbers

n = int(input("Enter the number: "))

for i in range(n):
    print(i)

If input = 5
Output:

0
1
2
3
4


---

5️⃣ Even and Odd Program

n = int(input("Enter the number: "))

for i in range(n):
    if i % 2 == 0:
        print("Even", i)
    else:
        print("Odd", i)

Explanation:

% gives remainder

If remainder is 0 → Even

Else → Odd



---

6️⃣ Addition of Two Numbers

a = int(input("Enter the number: "))
b = int(input("Enter the number: "))

c = a + b

print("Addition of a and b is", c)


---

🔹 Different Print Methods (From Your Image)

1️⃣ Normal Print

print(a, "+", b, "=", c)

2️⃣ Using format()

print("{} + {} = {}".format(a, b, c))

3️⃣ Using f-string (Best Method)

print(f"{a} + {b} = {c}")


---

7️⃣ Taking Two Inputs in One Line

a, b = map(int, input("Enter two numbers: ").split())

c = a + b
print(f"{a} + {b} = {c}")

Explanation:

.split() → separates values

map(int, ...) → converts to integers



---

8️⃣ Comparison Operators

Operator	Meaning

==	Equal
!=	Not equal
<	Less than
>	Greater than
<=	Less than or equal
>=	Greater than or equal



---

🔹 Not Equal !=

a = int(input("Enter the number: "))
b = int(input("Enter the number: "))

print(a != b)


---

🔹 Equal ==

print(a == b)


---

🔹 Less Than <

print(a < b)


---

🔹 Greater Than >

print(a > b)


---

🔹 Complex Comparison (From Image)

a = int(input("Enter the number: "))
b = int(input("Enter the number: "))
c = int(input("Enter the number: "))

print((a == b) == c)

This compares boolean result with number.


---

9️⃣ Logical Operators

Used to combine conditions.

Operator	Meaning

and	Both conditions must be True
or	At least one True
not	Reverse result



---

🔹 AND Operator

a = int(input("Enter the number: "))

if a >= 10 and a <= 18:
    print(a)

Condition must satisfy both.


---

🔹 OR Operator

a = int(input("Enter the number: "))

if a >= 18 or a == 10:
    print(a)

Only one condition needs to be true.


---

🔹 AND with Two Inputs

a = int(input("Enter the number: "))
b = int(input("Enter the number: "))

print(a == 5 and b == 6)


---

🔹 OR Example

print(a == 5 or b == 6)


---

🔹 NOT Operator

print(not(a == 5))

If condition is True → makes False
If False → makes True


---

🔟 Chained Comparison

a = int(input("Enter the number: "))

if 10 <= a <= 20:
    print("Number is between 10 and 20")

This is shorter way of:

if a >= 10 and a <= 20:


---

📌 Important Concepts Covered from All Images

✔ Integer & Float Division
✔ Input & Type Conversion
✔ If-Else
✔ Voting & Adult Program
✔ For Loop
✔ Even/Odd
✔ Addition Program
✔ Multiple Print Methods
✔ Taking Multiple Inputs
✔ Comparison Operators
✔ Logical Operators
✔ Chained Conditions


---

🎯 You Have Completed Basic Python Level 1

You now understand:

Variables

Input/Output

Conditions

Loops

Operators


