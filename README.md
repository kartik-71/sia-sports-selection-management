# SIA Sports Hub

Create a complete responsive web application named:

"SIA Sports Selection and Management Portal"

Tech Stack:

Frontend: HTML5, CSS3, JavaScript, Bootstrap

Backend: PHP

Database: MySQL

Charts: Chart.js

Project Type:

College Final Year Project (BSc IT Semester 5)

Main Objective:

The system should manage sports selection, student performance, attendance tracking, and achievers display for SIA College.

---------------------------------------------------

1️⃣ HOMEPAGE

---------------------------------------------------

Design a modern sports-themed homepage with:

- College logo and name at top

- Navigation bar:

  Home

  About Sports

  Achievers

  Login

  Register

  Contact

Sections:

- Hero section with sports background image

- About SIA Sports section

- Sports offered (Cricket, Football, Basketball, Athletics, etc.)

- Achievers section (cards with image, name, sport, achievement)

- Footer with contact details and social media icons

Make it stylish, dark theme with gradient highlights.

---------------------------------------------------

2️⃣ USER REGISTRATION SYSTEM

---------------------------------------------------

Create a student registration form with:

Fields:

- Full Name

- Username

- Email

- Password

- Confirm Password

- Course

- Year

Features:

- Prevent duplicate usernames

- Password hashing using PHP

- Validation

- Success message + redirect to login

---------------------------------------------------

3️⃣ LOGIN SYSTEM

---------------------------------------------------

Create login page for:

- Students

- Admin (separate login option)

Features:

- Session management

- Password verification

- Redirect to respective dashboards

---------------------------------------------------

4️⃣ STUDENT DASHBOARD

---------------------------------------------------

After login, student can:

- View profile

- View sports performance

- View attendance percentage

- View selection status

- View announcements

Display:

- Charts using Chart.js

- Performance graph

- Attendance pie chart

---------------------------------------------------

5️⃣ ADMIN DASHBOARD

---------------------------------------------------

Admin features:

- Add Sports

- Add Achievers

- Add Students

- Update Performance

- Mark Attendance

- View All Students

- Delete/Update Records

Include:

- Dashboard statistics (Total Students, Total Sports, Selected Players)

- Graphical analytics

- Table management system

---------------------------------------------------

6️⃣ DATABASE STRUCTURE

---------------------------------------------------

Create MySQL tables:

users

students

sports

achievers

performance

attendance

admin

Use proper primary keys and foreign keys.

---------------------------------------------------

7️⃣ SECURITY FEATURES

---------------------------------------------------

- Use password_hash() and password_verify()

- Session authentication

- Prevent SQL injection

- Logout functionality

- Role-based access (admin/student)

---------------------------------------------------

8️⃣ DESIGN REQUIREMENTS

---------------------------------------------------

- Fully responsive

- Professional UI

- Dark sports theme

- Smooth hover effects

- Clean dashboard layout

- Use cards and modern fonts

---------------------------------------------------

9️⃣ EXTRA FEATURES

---------------------------------------------------

- Search students

- Filter by sport

- Export data (optional)

- Display top performers

- Notification section

---------------------------------------------------

Make the project structured in folders:

/sia_sports_portal

   index.php

   login.php

   register.php

   db.php

   /admin

   /student

   /assets

   /css

   /js

   /images

Generate complete working code structure.

This project was built with [Lovable](https://lovable.dev).

**Live app**: https://athletic-realm-manager.lovable.app

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/5d654ba8-044a-4b0a-8c59-82d674841e2b).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
