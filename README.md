# 🧠 Java File I/O Practice Activities  
### Focus: Using BufferedReader and BufferedWriter

This set of activities will help you practice reading from and writing to text files in Java using **BufferedReader** and **BufferedWriter**.

---

## ✍️ Activity 1: Create and Write to a File
Write a program that:
1. Creates a text file called `students.txt`.
2. Prompts the user to enter the names of five students.
3. Writes each name to the file, one per line.
4. Displays a message confirming that the file has been created successfully.

---

## ✍️ Activity 2: Write Student Grades to a File
Write a program that:
1. Creates a file named `grades.txt`.
2. Prompts the user for a student’s name and their grade.
3. Writes the data in the format `Name,Grade` for five students.
4. Confirms when the file writing is complete.

---

## 📖 Activity 3: Read and Display File Contents
Write a program that:
1. Opens and reads data from `students.txt`.
2. Displays each line exactly as it appears in the file.
3. Closes the file after reading.

---

## 📖 Activity 4: Read and Format Data
Write a program that:
1. Reads data from `grades.txt` (data is stored as `Name,Grade`).
2. Splits each line using a comma `,`.
3. Displays each student’s name and grade in a neat, readable format:

---
---
---
# Challenge yourself 
### Theme: Using JFrame Buttons to Create and Write to a File  

## 🎯 Objective
In this activity, you will design a simple **Java Swing application (JFrame)** that interacts with a text file using buttons and a text field. The program will allow a user to **create** a file and **save information** entered in a text field.

---

## 🧱 Task Description

### Step 1: GUI Design
Design a JFrame with the following components:
- A **JTextField** for entering information (e.g., student name, message, etc.)
- A **“Create File”** button to create a new text file.
- A **“Save Information”** button to write whatever is typed in the text field into the file.
- A **JLabel** to display success or error messages (e.g., “File created successfully!” or “Information saved!”).

---

### Step 2: Functionality Requirements

#### 1. Create File Button
- When the user clicks the **“Create File”** button:
  - A new file (e.g., `student_info.txt`) must be created.
  - A message should appear confirming that the file has been created.
  - If the file already exists, display a message indicating that the file is already available.

#### 2. Save Information Button
- When the user clicks the **“Save Information”** button:
  - The program should take the text entered in the JTextField.
  - Write it to the text file created earlier (using `BufferedWriter`).
  - Display a success message once the data has been saved.
  - If no file exists yet, display an error message like “Please create a file first.”

#### 3. Input Field
- The JTextField should allow the user to type any string (e.g., name, comment, student ID).
- After saving, the field should clear automatically to allow for new input.

---

### 💡 Optional Enhancements
If you want to make the application more interesting:
- Add a **“View File Contents”** button to display all the text from the file in a **JTextArea**.
- Add a **timestamp** next to each entry when saving.
- Save each new entry on a **new line** instead of overwriting previous content.

