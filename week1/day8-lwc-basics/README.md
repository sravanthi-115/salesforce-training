# Day 8 - Lightning Web Components (LWC)

---

# 📌 What is LWC?

Lightning Web Components (LWC) is a modern UI framework used in Salesforce to build reusable and interactive user interfaces.

LWC is based on modern web technologies like:

- HTML
- JavaScript
- CSS
- Metadata Configuration (XML)

LWC helps developers build fast, reusable, and scalable Salesforce applications.

---

# 📌 Why Salesforce Uses LWC

Salesforce uses LWC because it:

- Improves UI performance
- Supports reusable components
- Uses modern web standards
- Creates better user experience
- Makes applications easier to maintain

LWC follows component-based architecture where UI is broken into smaller reusable parts.

---

# 🖥️ UI Thinking Exercise (College Management System)

### 1️⃣ Student Registration Form

Used for student admission and registration.

### 2️⃣ Course Dashboard

Displays available courses, seats, and faculty information.

### 3️⃣ Attendance View

Shows attendance percentage and academic status.

### 4️⃣ Faculty Panel

Allows faculty to manage courses and students.

### 5️⃣ Notifications Widget

Displays reminders, alerts, and announcements.

---

# 🧩 Component Thinking

## Selected Screen: Student Dashboard

### Reusable Components

### Header Component

Displays student dashboard title and navigation.

### Student Information Component

Shows student profile details.

### Attendance Component

Displays attendance percentage and academic progress.

### Notification Component

Shows alerts and important updates.

### Course Details Component

Displays enrolled course information.

---

## Why Reusable Components Are Useful

Reusable components help because they:

- Reduce repeated work
- Improve code maintainability
- Make UI easier to update
- Improve consistency
- Increase development speed

For example, the Notification Component can be reused across student, faculty, and admin dashboards.

---

# ⚖️ Frontend vs Backend Thinking

| Task                       | Frontend (UI) | Backend (Apex) |
| -------------------------- | ------------- | -------------- |
| Button Click               | ✅            | ❌             |
| Notification Display       | ✅            | ❌             |
| Fee Calculation            | ❌            | ✅             |
| Data Validation            | ❌            | ✅             |
| Student Registration Form  | ✅            | ❌             |
| Database Record Processing | ❌            | ✅             |

---

## Example Understanding

### Frontend/UI Logic

Frontend handles:

- User interface
- Button clicks
- Input forms
- Displaying notifications
- Showing data

### Backend/Apex Logic

Backend handles:

- Business rules
- Data validation
- Fee calculation
- Database operations
- Complex automation logic

---

# 💡 Reflection

## Why Do Modern Enterprise Systems Use Component-Based UI Architecture?

Modern enterprise systems use component-based architecture because it improves scalability, reusability, and maintainability.

Breaking UI into reusable components makes applications easier to manage and faster to develop.

It also improves consistency across large systems and reduces repeated work.

---

# ✍️ Revision Questions

---

## 1️⃣ What is a component?

A component is a reusable part of a user interface designed for a specific purpose.

Example: Header, notification widget, or attendance panel.

---

## 2️⃣ Why are reusable components useful?

Reusable components save time, improve consistency, and reduce repeated work.

---

## 3️⃣ Difference Between Frontend and Backend

| Frontend            | Backend                |
| ------------------- | ---------------------- |
| User interface      | Business logic         |
| Visible to users    | Runs behind the scenes |
| Handles interaction | Handles processing     |

---

## 4️⃣ Why did Salesforce move toward LWC?

Salesforce moved toward LWC because it is faster, modern, lightweight, and based on web standards.

---

## 5️⃣ Why is UI important in enterprise systems?

UI helps users interact with systems efficiently and improves user experience.

---

## 6️⃣ Why should systems separate UI and business logic?

Separation improves maintainability, scalability, and system organization.

---

## 7️⃣ What security risks exist in enterprise applications?

Risks include:

- Unauthorized access
- Data leakage
- Permission misuse
- Security vulnerabilities

---

## 8️⃣ Why should developers think modularly?

Modular thinking improves reusability, maintainability, and scalability.

---

# 📚 Trailhead Modules Completed

- Lightning Web Components Basics
- Secure Server-Side Development

---

# 🎯 Learning Outcome

Learned:

- What Lightning Web Components are
- Modern Salesforce UI architecture
- Component-based thinking
- Frontend vs backend separation
- Reusable UI design
- Security awareness
