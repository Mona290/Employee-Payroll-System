# Employee Payroll System

The Employee Payroll System is a Java application designed to manage employee information and calculate salaries for both full-time and part-time employees.

# Features

1.Employee Types: The system supports two types of employees: Full-time and Part-time.

2.Calculation of Salary: Calculates salaries based on the specific rules for each employee type.

3.Employee Management: Add employees, remove employees, and display the current list of employees.

# How to Use
Clone the Repository: Clone this repository to your local machine using the following command:

git clone https://github.com/your-username/employee-payroll-system.git

# Compile and Run:

Navigate to the project directory.

Compile the Java files:

javac Main.java

# Run the application:

java Main

# Usage:

The Main class contains the main method that demonstrates the functionality of the Employee Payroll System.
Modify the Main class to create, add, remove, or display employees as needed for your use case.

# Example Usage

Here's an example usage demonstrating how to create employees, add them to the system, and remove an employee:



  public class Main {

    public static void main(String[] args) {
    
        PayrollSystem payrollSystem = new PayrollSystem();
        
        FullTimeEmployee emp1 = new FullTimeEmployee("Vikas", 101, 70000.0);
        PartTimeEmployee emp2 = new PartTimeEmployee("Mona", 102, 40, 15.0);
        
        payrollSystem.addEmployee(emp1);
        payrollSystem.addEmployee(emp2);
        System.out.println("Initial Employee Details: ");
        payrollSystem.displayEmployees();
        
        System.out.println("\nRemoving Employees....");
        payrollSystem.removeEmployee(102);
        System.out.println("\nRemaining Employees Details: ");
        payrollSystem.displayEmployees();
    }


# Contributing

Feel free to contribute to this project by forking the repository and submitting pull requests.

# License

This project is licensed under the MIT License.
