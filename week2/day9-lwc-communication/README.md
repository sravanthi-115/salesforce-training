# Day 9 - LWC Communication and Data Flow

---

# 📌 Component Communication

Component communication helps Lightning Web Components exchange data and interact with one another.

Communication is important because enterprise applications contain multiple reusable components that must work together.

### Common Communication Types

### Parent to Child Communication

A parent component sends data to a child component.

Example:
Student Dashboard → Attendance Component

The dashboard sends student details to the attendance component.

---

### Child to Parent Communication

A child component sends information back to the parent using events.

Example:
Attendance Component → Student Dashboard

The attendance component updates attendance information and informs the dashboard.

---

### Event-Based Communication

Components react to user actions and system events.

Example:
Button Click → Trigger Notification Component

---

# 🖥️ Dashboard Architecture

---

## 🎓 Student Dashboard

### Components

- Header Component
- Student Profile Component
- Attendance Component
- Course Details Component
- Notification Component

### Component Communication

- Student Profile Component sends data to Attendance Component
- Course Details Component updates Notification Component
- Notification Component displays alerts to students

---

## 👨‍🏫 Faculty Dashboard

### Components

- Header Component
- Faculty Profile Component
- Course Management Component
- Attendance Monitoring Component
- Notification Component

### Component Communication

- Course Management Component updates Attendance Monitoring Component
- Notification Component alerts faculty about course changes

---

## 🛠️ Admin Dashboard

### Components

- Header Component
- Student Management Component
- Faculty Management Component
- Course Management Component
- Reports Component

### Component Communication

- Student Management Component updates Reports Component
- Faculty Management Component updates Course Management Component

---

# 🔄 Data Flow Thinking

## Example: Student Registration Process

### Step 1 - UI (Frontend)

Student fills registration form and clicks submit button.

---

### Step 2 - Validation Rules

Validation checks:

- Email format
- Required fields
- Duplicate registration

Invalid data is blocked.

---

### Step 3 - Flow Executes

Flow:

- Sends registration confirmation
- Notifies admin
- Updates registration status

---

### Step 4 - Apex Logic Executes

Apex handles:

- Advanced eligibility logic
- Course seat allocation
- Complex business rules

---

### Step 5 - Database Stores Records

Salesforce stores:

- Student details
- Course enrollment
- Registration information

---

### Step 6 - Notification Display

Student receives:

- Confirmation message
- Registration status
- Notifications

---

# ⚖️ Aura vs LWC

| Aura                            | LWC                            |
| ------------------------------- | ------------------------------ |
| Older Salesforce UI framework   | Modern Salesforce UI framework |
| Slower performance              | Faster performance             |
| Less aligned with web standards | Uses modern web standards      |
| More complex structure          | Lightweight and reusable       |

---

## Why Salesforce Moved from Aura/Visualforce to LWC

Salesforce moved toward LWC because it:

- Improves performance
- Uses reusable components
- Follows modern web standards
- Provides better scalability
- Improves maintainability

LWC helps developers build modern enterprise applications efficiently.

---

# 💡 Reflection

## Why Do Enterprise Applications Need Modular Architecture?

Enterprise applications are large and complex.

Modular architecture helps because it:

- Improves maintainability
- Supports reusable components
- Reduces repeated work
- Makes updates easier
- Improves scalability

Without modular systems, applications become difficult to manage and maintain.

---

# ✍️ Revision Questions

---

## 1️⃣ Why do components communicate?

Components communicate to exchange information and work together in a complete system.

---

## 2️⃣ Difference Between Parent-Child Communication and Events

| Parent-Child Communication | Events                         |
| -------------------------- | ------------------------------ |
| Data passed directly       | Data sent using actions/events |
| Parent controls child      | Child informs parent           |

---

## 3️⃣ Why is modular architecture useful?

It improves reusability, scalability, and maintainability.

---

## 4️⃣ Why did Salesforce move toward LWC?

Because LWC is faster, lightweight, reusable, and based on modern web standards.

---

## 5️⃣ What problems happen in tightly coupled systems?

Problems include:

- Difficult maintenance
- Poor scalability
- Repeated code
- Hard debugging

---

## 6️⃣ Why is frontend architecture important?

Frontend architecture improves user experience and organizes UI efficiently.

---

## 7️⃣ Why should UI and backend remain separate?

Separation improves maintainability and system organization.

---

## 8️⃣ Why do large systems need reusable modules?

Reusable modules save time, reduce repeated work, and improve consistency.

---

# 📚 Trailhead Modules Completed

- Lightning Web Components and Salesforce Data
- Communicate Between Lightning Web Components
- Visualforce Basics
- Aura Components Basics

---

# 🎯 Learning Outcome

Learned:

- Component communication
- Parent-child interaction
- Event-driven UI behavior
- Data flow inside applications
- Aura vs LWC concepts
- Modular enterprise architecture
