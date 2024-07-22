# Employee Table README

## Overview

The `Employee` table in this database stores information about employees, including their name, email ID, employee code, salary, role ID, role, and status. This README provides a description of the table structure and includes example data.

## Table Structure

### Columns

1. **id**: INT (Primary Key, Auto-increment) - Unique identifier for each employee.
2. **name**: VARCHAR(255) - Name of the employee.
3. **emailid**: VARCHAR(256) - Email address of the employee.
4. **code**: VARCHAR(256) - Unique code assigned to the employee.
5. **salary**: DECIMAL(10, 2) - Salary of the employee, stored with two decimal places for precision.
6. **role_id**: INT - ID representing the role of the employee.
7. **role**: VARCHAR(256) - Role description of the employee.
8. **status**: INT - Status of the employee (e.g., active or inactive).

## Example Data

Below are sample records inserted into the `Employee` table:

| id | name           | emailid                  | code   | salary    | role_id | role    | status |
|----|----------------|--------------------------|--------|-----------|---------|---------|--------|
| 1  | John Doe       | john.doe@example.com     | JD123  | 50000.00  | 1       | Admin   | 1      |
| 2  | Jane Smith     | jane.smith@example.com   | JS456  | 60000.50  | 2       | User    | 1      |
| 3  | Michael Brown  | michael.brown@example.com| MB789  | 75000.75  | 3       | Editor  | 0      |
| 4  | Emily Johnson  | emily.johnson@example.com| EJ987  | 55000.25  | 2       | User    | 1      |
| 5  | David Lee      | david.lee@example.com    | DL654  | 48000.00  | 1       | Admin   | 0      |

## Example Queries

### Retrieve all employees:

```sql
SELECT * FROM Employee;

