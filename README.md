# Student CGPA API

## Objective
Build a REST API using Express.js that manages student CGPA records stored in an in-memory JSON array.

## Features
- Manages student records (ID, Name, Branch, Semester, CGPA).
- 6 GET routes (4 static, 2 dynamic).
- CORS enabled.
- Error handling for non-existent records.

## Implemented Routes
1. `GET /students` - Returns all students.
2. `GET /students/topper` - Returns the student with the highest CGPA.
3. `GET /students/average` - Returns the average CGPA of all students.
4. `GET /students/count` - Returns the total number of students.
5. `GET /students/:id` - Returns student details by ID (Dynamic).
6. `GET /students/branch/:branchName` - Returns students belonging to a specific branch (Dynamic).

## Sample API URLs
- List all: `/students`
- Highest CGPA: `/students/topper`
- Average CGPA: `/students/average`
- Total count: `/students/count`
- Find by ID: `/students/1`
- Find by Branch: `/students/branch/CSE`

## Steps to Run Locally
1. Clone the repository.
2. Navigate to the project folder.
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the server:
   ```bash
   npm start
   ```
5. The API will be available at `http://localhost:3000`.

## Deployed Link
[Render Deployment Link](https://student-cgpa-api.onrender.com) (Example placeholder)
