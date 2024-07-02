# Course Management System - C# and Angular Project
**This repository holds the code for a course management system built with C# on the server-side and Angular on the client-side.**

## Features

- **User Management:**
  - Login and Registration options for users.
  - User information stored in sessionStorage (cleared on logout). Note: You might want to consider using localStorage instead of sessionStorage for persisting user information across sessions.
  - Distinction between user and lecturer roles.

- **Course Management:**
  - View a list of all existing courses.
  - View complete details of individual courses.
  - (Lecturer only) Add new courses.
  - (Lecturer only) Edit existing course details.
  - Input validation for course creation.
  - Dynamic subject entry for courses (adding/removing text boxes).

- **Course Display:**
  - Icons indicating course type (frontal or Zoom).
  - Search functionality for courses:
      - By name
      - By category
      - By learning method (frontal/Zoom)

## Technologies Used
  - C# (.NET)
  - Angular
  - Bootstrap
  - SweetAlert (and potentially other libraries)

## External Libraries
  - Bootstrap for styling.
  - SweetAlert (Swal) for user interactions.

## Usage

1. Clone the repository.
2. Run the backend server.
3. Run the Angular application.
4. Access the application through the provided URL.

## Contributors

- Esty - [GitHub: Estyxxxx](https://github.com/Estyxxxx)

## License

This project is licensed under the [MIT License](LICENSE).
