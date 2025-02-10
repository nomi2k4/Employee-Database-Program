Employee Database Program
A simple C++ program that stores and retrieves employee data.

Overview
This program defines a struct to represent employee data, including name, contact information, and salary. It then prompts the user to input data for up to 10 employees and displays the names of employees who reside in Islamabad and have a salary between 50,000 and 80,000.

Features
- Stores employee data in a struct
- Prompts user to input employee data
- Displays names of employees who meet specific criteria (Islamabad residence and salary range)

Requirements
- C++ compiler (e.g., GCC)
- Standard C++ libraries (e.g., iostream, string)

Usage
1. Compile the program using a C++ compiler (e.g., g++ employee_database.cpp -o employee_database)
2. Run the program (e.g., ./employee_database)
3. Follow the prompts to input employee data

Notes
- This program uses a fixed-size array to store employee data. For larger datasets, consider using dynamic memory allocation or a container class like std::vector.
- Error handling is minimal in this program. Consider adding checks for invalid user input or other potential errors.