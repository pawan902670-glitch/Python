📘 PYTHON TUPLE, SET, DICTIONARY – COMPLETE NOTES (COPY FORMAT)

---

🔷 TUPLE NOTES

🔹 1. Tuple Definition

- Tuple is an ordered, immutable collection
- Allows duplicate values
- Written using ( ) brackets

---

🔹 2. Creating a Tuple

t1 = (5, 7, 8.9, 'pawan')
print(t1)

---

🔹 3. Indexing

print(t1[0])   # 5
print(t1[-1])  # last element

---

🔹 4. Slicing

print(t1[1:3])

---

🔹 5. Tuple is Immutable

# ❌ Not allowed
# t1[1] = 10

---

🔹 6. Tuple Concatenation

t2 = (1, 2)
t3 = t1 + t2

---

🔹 7. Repetition

print(t2 * 3)

---

🔹 8. Membership

print(5 in t1)

---

🔹 9. Built-in Functions

print(len(t1))
print(max((1,2,3)))
print(min((1,2,3)))
print(sum((1,2,3)))

---

🔹 10. count() and index()

t = (1,2,2,3)
print(t.count(2))
print(t.index(3))

---

🔹 11. Packing & Unpacking

t = (1,2,3)
a,b,c = t

---

🔷 SET NOTES

🔹 1. Set Definition

- Set is unordered, mutable
- Does not allow duplicates
- Written using { }

---

🔹 2. Creating a Set

s1 = {1,2,3,4}
print(s1)

---

🔹 3. Adding Elements

s1.add(10)

---

🔹 4. Updating Set

s1.update([5,6,7])

---

🔹 5. Removing Elements

s1.remove(2)
s1.discard(3)

---

🔹 6. pop()

s1.pop()   # random element remove

---

🔹 7. Set Operations

a = {1,2,3}
b = {3,4,5}

print(a | b)   # union
print(a & b)   # intersection
print(a - b)   # difference

---

🔹 8. Membership

print(2 in s1)

---

🔹 9. Built-in Functions

print(len(s1))

---

🔹 10. clear()

s1.clear()

---

🔷 DICTIONARY NOTES

🔹 1. Dictionary Definition

- Dictionary is unordered, mutable
- Stores data in key : value pair
- Keys must be unique

---

🔹 2. Creating Dictionary

d1 = {
    "name": "pawan",
    "age": 20,
    "marks": 90
}
print(d1)

---

🔹 3. Accessing Values

print(d1["name"])
print(d1.get("age"))

---

🔹 4. Adding / Updating

d1["city"] = "Delhi"
d1["age"] = 21

---

🔹 5. Removing Elements

d1.pop("age")
del d1["marks"]

---

🔹 6. keys(), values(), items()

print(d1.keys())
print(d1.values())
print(d1.items())

---

🔹 7. update()

d1.update({"marks": 95})

---

🔹 8. clear()

d1.clear()

---

🔹 9. Membership

print("name" in d1)

---

🔹 10. Length

print(len(d1))

---

⚠️ IMPORTANT DIFFERENCE

Feature| List| Tuple| Set| Dictionary
Order| Yes| Yes| No| No
Mutable| Yes| No| Yes| Yes
Duplicates| Yes| Yes| No| Keys No
Syntax| []| ()| {}| {key:value}

---

✅ FINAL SUMMARY

- List → mutable, ordered
- Tuple → immutable, ordered
- Set → unordered, no duplicates
- Dictionary → key-value pairs

---
