
1️⃣ Bitwise Operators

🔹 What are Bitwise Operators?

Bitwise operators work on binary numbers (bits).

Every number inside a computer is stored in binary (0 and 1).

Example:

5 in binary = 0101
3 in binary = 0011


---

🔹 Types of Bitwise Operators

Operator	Symbol	Name

AND	&	Bitwise AND
OR	`	`
XOR	^	Bitwise XOR
NOT	~	Bitwise Negation
Left Shift	<<	Shift left
Right Shift	>>	Shift right



---

🔹 How They Work (Truth Table)

AND (&)

A	B	A & B

0	0	0
0	1	0
1	0	0
1	1	1


👉 Both must be 1 to get 1.

Example:

5 & 3
0101
0011
----
0001 = 1


---

OR (|)

| A | B | A | B | |---|---|-------| | 0 | 0 | 0 | | 0 | 1 | 1 | | 1 | 0 | 1 | | 1 | 1 | 1 |

👉 If any one is 1 → result is 1.


---

XOR (^)

A	B	A ^ B

0	0	0
0	1	1
1	0	1
1	1	0


👉 Same values → 0
👉 Different values → 1


---

NOT (~) – Negation

It flips bits.

~5
5 = 00000101
~5 = 11111010

In Python:

~5 = -6

Because Python uses 2’s complement representation.


---

2️⃣ Assignment Operators

🔹 What is Assignment?

Assignment operator is used to store a value in a variable.

a = 8

Here:

a is variable

= assigns value 8 to a



---

🔹 Compound Assignment Operators

These are shortcut operators.

Operator	Meaning	Example	Same As

+=	Add and assign	a += 5	a = a + 5
-=	Subtract and assign	a -= 5	a = a - 5
*=	Multiply and assign	a *= 5	a = a * 5
/=	Divide and assign	a /= 5	a = a / 5


Example:

a = 8
a += 5
print(a)

Output:

13


---

3️⃣ Membership Operators

🔹 What are Membership Operators?

Used to check whether a value exists inside a collection (like string, list, tuple).

Operator	Meaning

in	Value exists
not in	Value does not exist



---

🔹 Example with String

a = "Maharishi is a great university"

Check membership:

print("is" in a)

Output:

True

print("xyz" not in a)

Output:

True


---

Why use membership operators?

To:

Validate data

Check existence

Search inside string or list



---

4️⃣ Conditional (Ternary) Operator

🔹 What is it?

It is a short way to write an if-else statement.

Syntax:

value_if_true if condition else value_if_false


---

🔹 Example

e = "mojit@gmail.com"

print("Email is valid" if "@" in e else "Email Invalid")

How it works:

It checks: "@" in e

If True → prints "Email is valid"

If False → prints "Email Invalid"



---

🔹 Why use it?

Makes code shorter

Used for simple conditions

Improves readability



---

📌 Summary

Topic	Purpose

Bitwise Operators	Work on binary numbers
Assignment Operators	Store/update values
Membership Operators	Check existence in collection
Conditional Operator	Short if-else

