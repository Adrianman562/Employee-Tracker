## Description

Your EmployeeDB is a content management system (CMS) interface that allows non-developers to easily view and interact with their staff's information. 

## Usage
### User Story

```md
AS A business owner
I WANT to be able to view and manage the departments, roles, and employees in my company
SO THAT I can organize and plan my business
```

### Acceptance Criteria 

```md
GIVEN a command-line application that accepts user input
WHEN I start the application
THEN I am presented with the following options: view all departments, view all roles, view all employees, add a department, add a role, add an employee, and update an employee role
WHEN I choose to view all departments
THEN I am presented with a formatted table showing department names and department ids
WHEN I choose to view all roles
THEN I am presented with the job title, role id, the department that role belongs to, and the salary for that role
WHEN I choose to view all employees
THEN I am presented with a formatted table showing employee data, including employee ids, first names, last names, job titles, departments, salaries, and managers that the employees report to
WHEN I choose to add a department
THEN I am prompted to enter the name of the department and that department is added to the database
WHEN I choose to add a role
THEN I am prompted to enter the name, salary, and department for the role and that role is added to the database
WHEN I choose to add an employee
THEN I am prompted to enter the employee’s first name, last name, role, and manager, and that employee is added to the database
WHEN I choose to update an employee role
THEN I am prompted to select an employee to update and their new role and this information is updated in the database
```

## Installation
To run Your EmployeeDB locally:

1. Pull down and/or branch this repository
2. Run ```npm i``` to install all dependencies
3. Invoke app with ```node index.js``` </br> or ```nodemon index.js``` for nodemon
</br>
This is a command line application and has not been deployed. The following animation shows its use as directed: ![](assets/Screen%20Recording%202023-09-08%20at%207.11.18%20PM.mov)




## License
This project is licensed under the MIT license.

A short and simple permissive license with conditions only requiring preservation of copyright and license notices. Licensed works, modifications, and larger works may be distributed under different terms and without source code.<p/>For more information visit [MIT Licensing](https://choosealicense.com/licenses/mit/).

## Technologies Employed
* SQL
* Node
* Dotenv
* Inquirer
* JavaScript
* MySQL Server




- - -
© 2022 Your Employee-Tracker: Content Management System by Adrian Manzanares All Rights Reserved.
