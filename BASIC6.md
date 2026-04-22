

🔹 1. List Definition

- List is an ordered, mutable collection
- Allows duplicate values
- Can store multiple data types

---

🔹 2. Creating a List

list1 = [5, 7, 8.9, 'pawan', [6, 8, 9, 'shivam']]
print(list1)

---

🔹 3. Indexing

print(list1[0])   # First element
print(list1[4])   # Nested list

- Index starts from 0

---

🔹 4. Updating List (Mutable)

list1[3] = 'pranav'
print(list1)

---

🔹 5. List Concatenation

list2 = [3, 5, 6, 8]
list3 = [7, 8, 1, 'rakesh']

list_combined = list2 + list3 + list1
print(list_combined)

---

🔹 6. List Repetition

print(list2 * 4)

---

🔹 7. Membership Operators

x = 15 not in list2
print(x)

- "in" → check presence
- "not in" → check absence

---

🔹 8. Slicing (Reverse)

print(list1[2::-1])

---

🔹 9. Length of List

list4 = [1, 2, 3, 4]
print(len(list4))

---

🔹 10. append()

list4.append(13)
print(list4)

- Adds one element

---

🔹 11. extend()

list4.extend([6, 7, 8])
print(list4)

- Adds multiple elements

---

🔹 12. sum()

print(sum(list4))

- Works only with numbers

---

🔹 13. remove()

list4.remove(13)
print(list4)

- Removes value
- Returns None

---

🔹 14. pop()

print(list4.pop(0))
print(list4)

- Removes element using index
- Returns removed value

---

🔹 15. count()

print(list4.count(7))

- Counts occurrences

---

🔥 EXTRA / IMPORTANT OPERATIONS

---

🔹 16. insert()

list4.insert(1, 100)

---

🔹 17. index()

print(list4.index(7))

---

🔹 18. sort()

list4.sort()

---

🔹 19. reverse()

list4.reverse()

---

🔹 20. copy()

new_list = list4.copy()

---

🔹 21. clear()

list4.clear()

---

🔹 22. del keyword

del list4[0]
del list4

---

🔹 23. min() and max()

print(min([3,5,1]))
print(max([3,5,1]))

---

🔹 24. Nested List Access

print(list1[4][0])

---

🔹 25. Negative Indexing

print(list1[-1])

---

⚠️ IMPORTANT RULES

❌ Avoid:

list = [1,2,3]

✔ Use:

list_combined = [1,2,3]

---

🔄 append vs extend

list4.append([1,2])   # nested
list4.extend([1,2])   # separate

---

🔄 remove vs pop

Function| Work| Return
remove(x)| delete by value| None
pop(i)| delete by index| value

---

✅ FINAL SUMMARY

- List = ordered, mutable, allows duplicates
- Supports indexing & slicing
- Stores multiple data types
- Common functions:
  - append(), extend(), insert()
  - remove(), pop(), clear(), del
  - len(), sum(), count(), index()
  - sort(), reverse(), copy()

---
