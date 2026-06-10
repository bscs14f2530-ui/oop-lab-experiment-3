👨‍💼 Employee Management System (Unique ID Validation)
📌 Description

This is a simple C++ console-based program that stores details of 3 employees. It ensures that each employee has a unique employee number (ID) by checking for duplicates before accepting input.

🧾 Features
Stores employee number and salary
Ensures unique employee IDs (no duplicates allowed)
Uses array of structures
Displays all employee data
Input validation using loops
🛠️ Technologies Used
C++
iostream (standard input/output)
📂 Program Structure
Struct Used
struct Employee {
    int empNo;
    float salary;
};

Stores employee information (ID and salary).

▶️ How It Works
The program creates an array of 3 employees.
For each employee:
User enters employee number
Program checks if the ID already exists
If duplicate is found, user must re-enter ID
Then salary is entered
After input, all employee data is displayed.
💻 Sample Input
Enter employee number: 101  
Enter salary: 50000  

Enter employee number: 102  
Enter salary: 60000  

Enter employee number: 101  
Employee ID already exists. Enter Again  
Enter employee number: 103  
Enter salary: 55000  
📤 Sample Output
 --- Employee Data ---
Employee Number: 101
Salary: 50000
Employee Number: 102
Salary: 60000
Employee Number: 103
Salary: 55000
