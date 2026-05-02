# Student reoprt card
def grade(Percentage):
    if Percentage >= 90:
        return "A+"
    elif Percentage >= 75:
        return "A"
    elif Percentage >= 60:
        return "B"
    elif Percentage >= 50:
        return "C"
    else:
        return "Fail"

st = [ {"name":"Gunjan kumar","marks":[90,95,92]},
       {"name":"Durgesh kumar","marks":[79,89,60]},
       {"name":"Vishnu kumar","marks":[60,75,72]},
       {"name":"Arti kumari","marks":[78,89,75]},
       {"name":"Uttam Chaudhary","marks":[70,87,56]}
     ]
for student in st:
    total=sum(student["marks"])
    Percentage =total/len(student["marks"])
    G=grade(Percentage)
    student["total"]=total
    student["Percentage"] =Percentage
    student["G"]=G

search=input("Enter the name: ")
found=False
for student in st:
    if student["name"].lower()==search.lower():
        print("\nStudent Details:-")
        print(student["name"])
        print(student["marks"])
        print(student["total"])
        print(student["Percentage"])
        print(student["G"])
        found=True
        break
if not found:
    print(" Data is not found")
