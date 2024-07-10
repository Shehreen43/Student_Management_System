
# <h1>Student Management System </h1>
This project is a simple console-based Student Management System built using TypeScript and Inquirer.js. The system allows users to manage student data by performing various operations such as adding new students, generating unique student IDs, enrolling students in courses, viewing balances, paying tuition fees, showing student status, updating student details, and deleting students.

# Features
<h4>Add Student:</h4> Allows the user to add a new student by entering their name. The system generates a unique 5-digit student ID        for each new student.

Enroll Student in Course: Enrolls a student in a course by specifying the course name. Each course costs $600, which is added to the student's tuition balance.

View Balance: Displays the tuition balance of a selected student.

Pay Tuition: Allows the user to pay a specified amount towards a student's tuition balance.

Show Status: Displays all details of a selected student, including their name, student ID, enrolled courses, and tuition balance.

Update Student: Enables the user to update a student's name and enrolled courses.

Delete Student: Removes a student's record from the system.

# Technologies Used
TypeScript: A strongly typed programming language that builds on JavaScript, giving you better tooling at any scale.

Inquirer.js: A collection of common interactive command-line user interfaces.

Getting Started

# Prerequisites
Node.js: Ensure you have Node.js installed on your machine. You can download it from Node.js official website.
# Installation
Clone the Repository:

bash
Copy code
git clone https://github.com/your-repository/student-management-system.git
cd student-management-system

# Install Dependencies:

bash
Copy code
npm install
Compile TypeScript Code:

bash
Copy code
tsc
Running the Application
Start the Application:

bash
Copy code
node StudentManagementSystem.js
Follow the Prompts: The application will guide you through various operations via an interactive command-line interface.

# Usage
Add Student: Follow the prompt to enter the student's name. The system will generate a unique student ID.
Enroll Student in Course: Select a student and specify the course name to enroll them in the course.
View Balance: Select a student to view their current tuition balance.
Pay Tuition: Select a student and enter the amount to pay towards their tuition balance.
Show Status: Select a student to view their details, including name, student ID, enrolled courses, and balance.
Update Student: Select a student to update their name and enrolled courses.
Delete Student: Select a student to remove their record from the system.
Example
Here's a simple example of how the interaction with the system looks like:

# Main Menu:

sql
Copy code
Select an action:
> Add Student
  Enroll Student in Course
  View Balance
  Pay Tuition
  Show Status
  Update Student
  Delete Student
  Exit
Adding a Student:

yaml
Copy code
Enter student name: John Doe
Student John Doe added with ID: 10000
Enrolling in a Course:

yaml
Copy code
Select student: John Doe
Enter course name: Mathematics
Enrolled in course: Mathematics
Viewing Balance:

yaml
Copy code
Select student: John Doe
Tuition Balance: $600
# License
This project is licensed under the MIT License.

# Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

# Acknowledgements
Inquirer.js: For providing an excellent library to create interactive command-line user interfaces.
Contact
For any questions or suggestions, please contact [shehreenarshadarshad@gmail.com].

