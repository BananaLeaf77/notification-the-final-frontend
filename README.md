# 🎨 Notification System – Frontend

This is the **frontend** for my **college thesis project**, a system to notify parents via **WhatsApp and Email** if their child does not attend school.

---

## 🖥️ Features

* **Login & Authentication** (via backend API).
* **Dashboard** to manage:

  * Students
  * Parents
  * Users (teachers/admins)
  * Attendance records
  * Data change requests
* **Attendance Tracking**: view history of student absences.
* **Notification Management**: send WhatsApp & Email notifications through the backend.
* **Responsive Layout** using HTML, CSS, and JavaScript.

---

## ⚙️ Tech Stack

* **Frontend**: HTML, CSS, JavaScript
* **Charts**: For data visualization
* **Backend API**: Golang (Fiber) \[separate repo]
* **Database**: PostgreSQL (connected via backend)

---

## 📂 Project Structure (Simplified)

```
frontend/
 ├── assets/                # Static assets (images, icons, etc.)
 ├── charts/                # Chart components
 ├── components/            # Reusable HTML components
 ├── forms/                 # Form components
 ├── maps/                  # Map integration
 ├── tables/                # Data tables
 ├── index.html             # Main dashboard
 ├── login.html             # Login page
 ├── attendanceHistory.html # Student attendance history
 ├── addStudent.html        # Add new student
 ├── addUser.html           # Add new user
 ├── staffDetailStudent.html# Staff → student detail page
 └── ... (other pages)
```

---

## 🚀 Setup & Run

1. Clone this repo:

   ```bash
   git clone https://github.com/your-username/frontend-notification.git
   cd frontend-notification
   ```

2. Open `index.html` or `login.html` directly in a browser.
   (Or serve it with a simple HTTP server, e.g. Python:)

   ```bash
   python3 -m http.server 8081
   ```

3. Configure the **backend API base URL** inside your JS (if applicable), so the frontend can talk to the Go backend.

---

## 📘 Notes

* This frontend is tightly coupled with the [Notification Backend](https://github.com/your-username/notification-service).
* It requires the backend API to be running for login, student data, and notification features.
* Pages are structured per-feature (attendance, users, students, etc.) for clarity.

---

## 👨‍🎓 Author

* **Name**: (Your Full Name)
* **Project**: College Thesis
* **Goal**: Improve parental awareness by providing real-time absence notifications.

---
