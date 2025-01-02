# Project Title: Communication Calendar

An intuitive application for managing and tracking communication schedules for companies, ensuring streamlined interactions and efficient task management.

## Project Description

The **Communication Calendar** is an intuitive web application designed to help users and administrators manage and track communications with companies. It provides a comprehensive platform for scheduling, logging, and monitoring past and upcoming communications, ensuring streamlined communication management.

### Key Features:

1.**Admin Module**: Allows admins to set up companies, configure communication parameters like frequency and method, and manage communication data.

2.**User Module**: Enables users to view, log, and manage communications. It displays past and upcoming communications, providing a clear overview of interactions.

3.**Notification System**: Flags overdue communications and highlights those due today, helping users stay on top of important tasks.

4.**Communication Logging**: Users can log communication events with specific companies, including details like date, method, and notes.

5.**Dark Mode Support**: The application supports dark mode, ensuring a visually comfortable experience in low-light environments.

6.**Dynamic Filtering and Sorting**: Communications can be filtered and sorted based on their status (past vs. upcoming), with customizable sorting options.

This application is designed to simplify communication tracking and make the management process more efficient for both admins and users.

## Setup Instructions

### Prerequisites:
- Node.js (version 14 or higher)
- npm (Node Package Manager)

### Installation:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-project.git

2.Navigate to the project folder: cd your-project

3.Install dependencies: npm install

## Running the Application:
1.Start the development server: npm start

2.Open the application in your browser at http://localhost:5173.


## Known Limitations:

1. **Notification Accuracy**: 
   The notification system may show incorrect statuses if data (like communication frequency or logs) is inaccurate.

2. **Admin/User Separation**: 
   There's no clear distinction between admin and user roles at the authentication level. Both can access all functionalities, which might require future role-based access control.

3. **Data Validation**: 
   Deleting a company or communication method may cause orphaned records since dependencies are not strictly enforced.































