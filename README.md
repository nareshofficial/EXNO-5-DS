# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
# STEP 1: Include necessary library
import matplotlib.pyplot as plt

# Sample dataset
students = ['Alice', 'Bob', 'Charlie', 'David', 'Eva']
marks = [88, 72, 93, 85, 79]

# STEP 2: Line plot - Student vs Marks
plt.figure(figsize=(8, 5))
plt.plot(students, marks, marker='o', linestyle='-', color='blue')
plt.title("Student Marks - Line Plot")
plt.xlabel("Students")
plt.ylabel("Marks")
plt.grid(True)
plt.show()

# STEP 3: Bar Chart
plt.figure(figsize=(8, 5))
plt.bar(students, marks, color='orange')
plt.title("Student Marks - Bar Chart")
plt.xlabel("Students")
plt.ylabel("Marks")
plt.show()

# STEP 4: Pie Chart
plt.figure(figsize=(6, 6))
plt.pie(marks, labels=students, autopct='%1.1f%%', startangle=140)
plt.title("Student Marks Distribution - Pie Chart")
plt.axis('equal')
plt.show()

# Result:
 Include your result here
![image](https://github.com/user-attachments/assets/d4fe8196-7e3a-4263-a8a9-4f4fd7f4573d)
![image](https://github.com/user-attachments/assets/72579791-2ff6-4377-aea0-b647928abca3)
![image](https://github.com/user-attachments/assets/ee72a6a5-cdb9-4edd-88b9-ab525f373a2e)



