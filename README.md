# Assignment-5
 # Module 6: Data Structures and Strings in Python
 # Task 1: Create a Dictionary of Student Marks

# Create a dictionary of student marks
student_marks = {
    "Alice": 85,
    "Bob": 78,
    "Charlie": 92,
    "David": 74
}

# Ask user for student name
name = input("Enter the student's name: ")

# Check if name exists in dictionary
if name in student_marks:
    print(f"{name}'s marks: {student_marks[name]}")
else:
    print("Student not found.")

# Example Run ✅

Case 1: Student Exists

Enter the student's name: Alice
Alice's marks: 85


Case 2: Student Does Not Exist

Enter the student's name: John
Student not found.

# Task 2: Demonstrate List Slicing 

# Create a list from 1 to 10
numbers = list(range(1, 11))

# Extract the first five elements
extracted = numbers[:5]

# Reverse the extracted list
reversed_extracted = extracted[::-1]

# Print results
print("Original List:", numbers)
print("Extracted first five elements:", extracted)
print("Reversed extracted elements:", reversed_extracted)

# Example Run
Original List: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
Extracted first five elements: [1, 2, 3, 4, 5]
Reversed extracted elements: [5, 4, 3, 2, 1]
