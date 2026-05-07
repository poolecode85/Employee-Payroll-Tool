# Employee Payroll Tool

## Overview
The Employee Payroll Tool is a Python command-line application that calculates employee wages, including regular pay, overtime pay, and total payroll summaries for multiple employees. It simulates a basic payroll processing system using standard business rules and user input.

## Features
- Accepts multiple employee entries
- Calculates regular pay (up to 40 hours)
- Calculates overtime pay at 1.5x hourly rate
- Tracks cumulative payroll totals across all employees
- Displays formatted payroll breakdown per employee
- Generates final payroll summary report

## How It Works
1. The user enters an employee’s name, hours worked, and hourly pay rate  
2. The program calculates:
   - Regular pay
   - Overtime pay (if applicable)
   - Gross pay  
3. Results are displayed for each employee  
4. The system tracks totals for all employees entered  
5. Enter "done" to finish and display final summary report  

## Example Output
Employee Name: John Doe  
Hours Worked: 45  
Overtime Hours: 5  
Regular Pay: $800.00  
Overtime Pay: $112.50  
Gross Pay: $912.50  

## Technologies Used
- Python 3
- Functions
- Loops (while loop)
- Conditional statements (if/else)
- User input handling

## Purpose
This project was built to demonstrate foundational programming skills in Python, including control flow, function design, and data aggregation in a real-world payroll scenario.

## Future Improvements
- Export payroll data to CSV file  
- Add database storage for employees  
- Build a GUI version using Tkinter or a web interface  
- Improve input validation and error handling  

## Notes
This project was originally created as a class assignment and has been refactored and cleaned for portfolio presentation.
