# SQL Challenge

## Employee Database Project

This repository contains the files and SQL scripts necessary to create and query an employee database. The database schema is designed to manage employee records, departments, titles, salaries, and department assignments within the Pewlett Hackard company.

### Files Included

1. **Entity_Relationship_Diagram.png**
   - This file contains a visual representation of the database schema, illustrating the relationships between tables such as `employees`, `departments`, `titles`, `salaries`, `dept_emp`, and `dept_manager`.

2. **table_schemata.sql**
   - This SQL script includes the `CREATE TABLE` statements to generate the database tables. It defines the table structures, including data types, primary keys, foreign keys, and any necessary constraints.

3. **query.sql**
   - This file contains a set of SQL queries that can be run against the database to extract meaningful data, such as employee information, salary details, and department assignments.

### Database Schema

The database schema consists of the following tables:

- **departments**: Stores information about departments within the company.
- **dept_emp**: Records the assignment of employees to departments.
- **dept_manager**: Tracks which employees manage which departments.
- **employees**: Contains personal and employment details for each employee.
- **salaries**: Stores salary information for employees.
- **titles**: Lists job titles available within the company.