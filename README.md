
# SharePoint Login System (Power Apps Canvas App)

A role-based **login + user management** solution built with **Power Apps (Canvas App)** and **SharePoint Lists**.  
It supports **two roles**:

- **Admin** → can view who has logged in (audit/log list) and manage users
- **User** → can view only their own profile/credentials (no access to other users’ data)

> ⚡ This project focuses on clean UX, validation (real email format + password rules), and role-based access inside Power Apps.
##Demo

### Login Screen
![Login Screen](./login-2members.gif)

---

## ✨ Key Features

### ✅ Role-based experience
- Admin and User see **different screens and data**
- Navigation is controlled by the user’s role after login

### ✅ Strong input validation
- Email field validates proper email format (no fake/invalid formats)
- Password must meet defined criteria (example rules: length + uppercase + lowercase + number + special character)

### ✅ Login auditing (Admin)
- Tracks successful logins (who logged in + timestamp)
- Admin can review recent activity

### ✅ SharePoint as the backend
- Stores user records and login logs in **SharePoint Lists**
- Easy to update, maintain, and demo without a complex server setup

---

## 🧰 Tech Stack
- **Power Apps (Canvas App)**
- **SharePoint Online Lists**
- Optional: Power Automate (if used for logging/notifications)

---


