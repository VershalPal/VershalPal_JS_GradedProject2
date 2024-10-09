# Resume Viewer Web Application

## Project Overview
This is a web application that allows users to view candidate applications for various job openings. It includes a login page for user authentication and a resume page to browse and filter applicant details. Candidate data is stored in a JSON file, which is dynamically displayed.

## Features
- **Login Page**
  - Stores username and password in local storage.
  - Validates login credentials; incorrect entries show "Invalid username/password."
  - Prevents going back to the login page after a successful login.

- **Resume Page**
  - Displays applicant details fetched from a JSON file.
  - Next and Previous buttons to navigate through applicants.
  - Filter by job position; displays an error message if no matches are found.
  - Automatically hides Next/Previous buttons when appropriate (e.g., only one applicant).

## Technologies Used
- HTML5, CSS3, JavaScript (ES6)
- Local Storage (for login data)
- JSON (for applicant details)

## How to Use
1. **Login Page**: Enter a valid username and password. If correct, you'll be redirected to the Resume Page.
2. **Resume Page**: Browse through candidates using Next/Previous buttons. Filter applicants by job title using the search bar. If no results, a message will appear: “Invalid search or No applications for this job.”

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/resume-viewer.git
2. Open index.html in your browser to open the application.

## JSON Data Format
### Example structure:
[
  {
    "id": 1,
    "name": "John Doe",
    "email": "john.doe@example.com",
    "job_applied_for": "Front End Developer",
    "skills": ["HTML", "CSS", "JavaScript"],
    "experience": "3 years",
    "education": "B.Tech in Computer Science"
  }
]
