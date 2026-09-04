# cohort-9-mern-9816-muhammad
# NotesApp

NotesApp is a full-stack note management application developed using the MERN stack. It allows users to securely register and log in, create and manage personal notes, edit notes using a rich-text editor, and manage their profiles.

## Features

- User Registration and Login
- JWT-based Authentication and Authorization
- Create, View, Edit, and Delete Notes
- Rich Text Editor for Notes
- Note Categories and Creation Dates
- User Profile Management
- Profile Image Upload using Cloudinary
- Frontend and Backend Validation
- HTML Sanitization using DOMPurify
- JSON Import and Export
- Toast Notifications
- Pino Application Logging
- Unit Testing with Jest, React Testing Library, Mocha, Chai, and Sinon
- SonarQube Code Quality Analysis
- GitHub Actions CI Workflow

## Technologies Used

### Frontend
- React.js
- React Router
- Axios
- Tailwind CSS
- Tiptap
- DOMPurify
- React Toastify
- Jest
- React Testing Library

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcrypt
- Multer
- Cloudinary
- Pino
- Mocha
- Chai
- Sinon

## Security

The application uses JWT authentication, password hashing, protected routes, user-specific authorization, input validation, and HTML sanitization. Express framework information disclosure is also disabled using `app.disable("x-powered-by")`.

## Code Quality

SonarQube Cloud is integrated with the project to perform static code analysis and identify bugs, vulnerabilities, security hotspots, code smells, code duplication, maintainability issues, and test coverage.

GitHub Actions is used to automate the SonarQube analysis workflow.

## Project Purpose

This project was developed as part of a MERN internship to gain practical experience in full-stack development, REST APIs, authentication, database management, testing, Git/GitHub workflows, CI/CD, and code quality practices.

## Author

**Muhammad Touqeer Ahmad**

BS Software Engineering  
University of Gujrat
