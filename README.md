# group-project
name = input("Enter student name: ")
m1 = float(input("Enter marks in Subject 1: "))
m2 = float(input("Enter marks in Subject 2: "))
m3 = float(input("Enter marks in Subject 3: "))
total = m1 + m2 + m3
percentage = total / 3
if percentage >= 90:
    grade = "A+"
elif percentage >= 80:
    grade = "A"
elif percentage >= 70:
    grade = "B"
elif percentage >= 60:
    grade = "C"
else:
    grade = "D"
print("\n--- Student Result ---")
print("Name:", name)
print("Total:", total)
print("Percentage:", percentage)
print("Grade:", grade)
