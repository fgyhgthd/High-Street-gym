🏋️‍♂️ High-Street-Gym Full Stack Web Application
Welcome to the official preview of the High Street Gym Full Stack Web Application.

This mobile-first application supports members, trainers, and managers in managing health and fitness activities both online and internally.

✨ Key Features
✅ Member-Only Sign-Up
Public registration is available only for members. Trainers and managers are registered internally.

🔐 User Authentication
Secure login system using email and password. User roles include:

Member — Book classes, view timetable, post to blog, and export data

Trainer — Manage sessions and export weekly schedules

Manager — Access internal tools (backend only)

📅 Responsive Timetable Viewer
View weekly gym session schedules across all locations. Fully responsive for mobile, tablet, and desktop devices.

🧘 Class Booking System
Members can:

View available sessions

Select a trainer when multiple are available

Book sessions directly from the schedule

🗓️ Booking Management
Members can review and cancel upcoming class bookings at any time.

🧾 XML Export (Frontend Only)
Trainers: Export weekly session schedules (for external calendars)

Members: Export past booking data (for fitness tracking apps)

📝 Member Microblog
Create and delete personal posts

View a shared community feed
(Admin moderation supported)

👤 Profile Management
All users can update personal details — including name, contact information, and password.

🧭 Project Structure
This project includes two websites:

1. 🔧 Backend Interface
Location: /backend/

Used by: Members, Trainers, and Managers

Built with: Node.js, Express.js

Purpose:

Internal user/session management

Booking logic and validation

Admin-only access and logging

Note: XML export features are not supported here.

Access: Requires login credentials (see below)

2. 🌐 Frontend Application
Location: /frontend/

Built with: React.js

Used by: Members and Trainers

Purpose:

Public-facing interface for booking, blogging, schedule viewing

Supports all key features, including XML export

Note: Managers do not have access to the frontend

🔐 Login Details
➤ Manager (Backend Only)
Role: Manager

Email: mayurbhagat@outlook.com

Password: Viren001@

➤ Trainer
Role: Trainer

Email: mayurbhagat9@outlook.com

Password: Viren001@

➤ Member
You can create your own account directly from the website’s signup page.

⚠️ License
This project is licensed. Please review the license terms before modifying or redistributing any part of the codebase.

© 2025 High Street Gym — Made with ❤️ by Mayur Bhagat
