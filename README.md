This is Spring Boot CRUD application demonstration with Thymeleaf frontend

## Prerequisites

* MySQL

## Installation

* Pull out the code using [Git](https://git-scm.com/downloads):

```shell
https://github.com/ashaleyko/employees-directory.git
cd employees-directory
```
* Run the database scripts to create a user and load sample data  
  a. src/scripts/sql/01-create-user.sql  
  b. src/scripts/sql/02-employee.sql

## Usage

```shell
./mvnw spring-boot:run
```

## Demo
Create  
![Alt text](docs/screenshots/employees-directory-save.png?raw=true "Save")

Read  
![Alt text](docs/screenshots/employees-directory-list.png?raw=true "List")

Update  
![Alt text](docs/screenshots/employees-directory-update.png?raw=true "Update")

Delete  
![Alt text](docs/screenshots/employees-directory-delete.png?raw=true "Delete")
