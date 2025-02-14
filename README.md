# Kanban-Board
Kanban Board with Secure Authentication

📌 Project Overview

This project is a Kanban board application featuring a secure login system using JSON Web Tokens (JWT). Users can authenticate, manage tasks, and experience session management with automatic logout upon inactivity.

🚀 Features

User Authentication: Secure login with JWT-based authentication.

Protected Routes: Users must log in to access the Kanban board.

Persistent Sessions: JWT is stored securely in local storage for future authentication.

Session Expiry: Automatic logout after inactivity.

Error Handling: Informative error messages for invalid credentials.

Kanban Functionality: Create, edit, and move tasks across columns.
🔑 Authentication Flow

User Login: Enter valid credentials → JWT is generated and stored in HttpOnly cookies.

Access Control: Protected routes require a valid JWT.

Invalid Login: Error message is displayed.

Logout: JWT is removed, redirecting to login page.

Session Expiry: Auto-logout after inactivity.

Github: WilliamSheere

E-mail: Sheerebilly@yahoo.com