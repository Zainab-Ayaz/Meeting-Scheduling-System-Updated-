# Meeting Schedule System 🎓📅

A web-based portal system to schedule and manage meetings within a university. Built using **PHP**, **MySQL**, **HTML**, **CSS**, and **JavaScript**, it supports room, teacher, and slot availability checking, faculty listings, and calendar integration.

---

## 🔧 Features

- 🔐 **Login System** for authorized users
- 🗓️ **Schedule Meetings** with teacher, room, and time slot selection
- ✅ **Conflict Detection** for room, slot, and teacher availability
- 📋 **View Meetings** in a structured table
- 👨‍🏫 **Faculty List** showing all registered faculty with designation
- 🧭 **Dashboard Portal** with sidebar and calendar
- 🎨 Styled with a **purple-themed professional layout**

---

## 📁 Project Structure

/meeting-schedule-system/
│
├── dashboard.php # Main dashboard with calendar
├── login.php # Login page
├── logout.php # Logout logic
├── schedule.php # Form to schedule new meetings
├── view_meetings.php # View all scheduled meetings
├── faculty_list.php # View all faculty members
├── style.css # Styling (purple portal theme)
├── db.php # Database connection
├── auth.php # Authentication check
└── README.md # This file

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: PHP
- **Database**: MySQL
- **Server**: XAMPP / Apache (Localhost)

---

## 🚀 How to Run

1. Install [XAMPP](https://www.apachefriends.org/index.html)
2. Place the folder in `C:\xampp\htdocs\`
3. Start Apache and MySQL via XAMPP Control Panel
4. Create the database and import `meeting_schedule_db.sql`
5. Visit: [http://localhost/meeting-schedule-system/login.php](http://localhost/meeting-schedule-system/login.php)

---

## 👤 Admin Credentials

Username: admin@uni.edu
Password: admin123

*(Modify in your database as needed)*

---

## 📄 License

This project is open-source and can be used for educational and development purposes.

---

## 💡 Future Improvements

- Email/SMS notifications
- Multiple user roles (admin/staff/teacher)
- Drag-and-drop calendar booking
