# Task-ManagementFull-Stack Task Management Web Application
This is a feature-rich, full-stack web application designed for multi-user task management. It features real-time data synchronization, an interactive data visualization dashboard, and robust user account management, all powered by a Firebase backend.

✨ Live Demo
[Link to your live demo will go here once the project is deployed.]

🚀 Key Features
This application goes beyond a simple to-do list, offering a comprehensive set of features for an enhanced user experience:

🔐 Secure User Authentication: Full signup and login functionality using Firebase Authentication. Each user's data is private and secure.

⚡ Real-time Database: Built with Firebase Firestore, allowing tasks and lists to sync instantly across different sessions without needing to refresh the page.

📋 Multi-List Management: Users can create, manage, and switch between multiple task lists (e.g., "Work," "Personal," "General").

🗓️ Task Scheduling: Add tasks with specific start and end dates and times.

📊 Interactive Dashboard: A dedicated dashboard page with data visualizations powered by Chart.js:

A doughnut chart showing the overall status of completed vs. pending tasks.

A bar chart breaking down the number of tasks in each list.

🔍 Date-Range Search: A powerful search utility on the dashboard to find tasks within a specific date range.

⚙️ Advanced User Settings: A settings page where users can:

Update their display name.

Request a password reset email.

Export all their task data as a JSON file.

Permanently delete their account and all associated data.

🌓 Light & Dark Themes: A sleek, modern UI with a theme switcher for user preference.

📱 Fully Responsive: The layout is optimized for a seamless experience on desktops, tablets, and mobile devices.

🛠️ Technologies Used
This project was built with a modern, lightweight tech stack:

Frontend: HTML5, Tailwind CSS, Vanilla JavaScript (ES6 Modules)

Backend & Database: Firebase (Authentication & Firestore)

Data Visualization: Chart.js

Icons: Lucide Icons

Setup and Installation
To run this project on your local machine, follow these steps:

Clone the repository:

git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)

Set up Firebase:

Go to the Firebase Console and create a new project.

Enable Authentication > Sign-in method > Email/Password.

Create a Firestore Database and start it in Test mode.

Get Firebase Configuration:

In your Firebase project settings, find your Web App's configuration keys (firebaseConfig object).

Add Config to the Project:

Open the task-manager.html file.

Find the <script type="module"> tag at the bottom.

Replace the placeholder firebaseConfig object with the one you copied from your Firebase project.

Run the Application:

Simply open the task-manager.html file in your web browser. You can now sign up, log in, and use the application.

👤 Author
Shubhankar Singh
