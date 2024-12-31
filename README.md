# project
<br>
Auther : Vaibahv Katkar
# Student Registration and Admin Panel Website

This project is a simple website with two main sections: **Home** and **Admin**. The website allows users to register their information as students and view it through an admin panel after login. The information is stored in a MongoDB database and retrieved for display in a user-friendly card format.

## Features

- **Home Page**:
  - Displays a "Join Now" button that leads to a form where users can enter basic student information (e.g., name, email, course).
  - After submission, a success page is shown with a confirmation message and a button to return to the homepage.

- **Admin Panel**:
  - A login page where the admin can log in with a valid username and password.
  - After logging in, the admin can view all registered students' information, displayed in a card layout.
  
- **Database**:  
  - Stores student information using MongoDB, retrieved and displayed dynamically.
  
## Technologies Used

- **Frontend**: HTML, CSS, EJS
- **Backend**: Node.js with Express.js
- **Database**: MongoDB with Mongoose
- **API**: RESTful API for communication between frontend and backend
- **Authentication**: Simple admin login system

## Setup Instructions

Follow these steps to run the project locally:

### 1. Clone the repository:
```bash
git clone https://github.com/yourusername/student-registration-admin-panel.git
