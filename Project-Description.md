# Student Management REST API

Build a Student Management REST API using **Express.js, MongoDB, and Mongoose**.

## CRUD Operations

Implement the following CRUD operations:

- Create a new student
- Get all students
- Get a student by ID
- Update a student
- Delete a student

## Student Fields & Validation Rules

### 1. Name
- Required
- 3 to 50 characters
- Remove leading and trailing spaces

### 2. Email
- Required
- Must be a valid email address
- Store in lowercase
- Must be unique

### 3. Age
- Required
- Value should be between 18 and 60

### 4. Course
- Required
- Allowed values:
  - MERN
  - MEAN
  - Python
  - Java Full Stack
  - AI Engineering

### 5. Skills
- Optional
- Store as a list of strings
- Default value: Empty list (`[]`)

### 6. Fees Paid
- Optional
- Cannot be negative
- Default value: `0`

### 7. Active Status
- Optional
- Boolean value (`true` / `false`)
- Default value: `true`