print("Enter marks of 5 subjects out of 100:")
subject1 = float(input("Enter marks for Subject 1: "))
subject2 = float(input("Enter marks for Subject 2: "))
subject3 = float(input("Enter marks for Subject 3: "))
subject4 = float(input("Enter marks for Subject 4: "))
subject5 = float(input("Enter marks for Subject 5: "))
total_marks = subject1 + subject2 + subject3 + subject4 + subject5
average_marks = total_marks 
if average_marks >= 90:
    grade = "A"
elif average_marks >= 75:
    grade = "B"
elif average_marks >= 50:
    grade = "C"
else:
    grade = "F"
print("\n----- Student Result -----")
print(f"Total Marks   : {total_marks}")
print(f"Average Marks : {average_marks:.2f}")
print(f"Grade         : {grade}")
