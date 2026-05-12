# Day 4 - Salesforce Flow Builder

---

# 📌 What is Flow Builder?

Flow Builder is a no-code automation tool in Salesforce used to automate business processes using visual workflows.

It helps organizations:

- Reduce manual work
- Automate repetitive tasks
- Improve productivity
- Maintain process consistency

Flow Builder allows admins and developers to build automation without writing code.

---

# ⚡ Why Businesses Need Automation

Businesses automate processes because:

- Manual work consumes time
- Human errors increase
- Repetitive tasks reduce productivity
- Large-scale operations become difficult to manage manually

Automation improves:

- Speed
- Accuracy
- Efficiency
- Consistency

---

# 🔄 Types of Flows in Salesforce

---

## 1️⃣ Screen Flow

Screen Flow is an interactive flow that collects input from users through screens.

### Examples

- Student registration form
- Feedback collection form
- Admission application process

### Features

- User interaction
- Input forms
- Guided workflows

---

## 2️⃣ Record Triggered Flow

Record Triggered Flow runs automatically when a record is created, updated, or deleted.

### Examples

- Send email after student registration
- Update course seats automatically
- Notify faculty when course becomes full

### Features

- Fully automated
- Runs in background
- No user interaction required

---

# 🎓 Automation Ideas for College Management System

---

## 1️⃣ Auto Email After Registration

### Process

Automatically send confirmation email after student registration.

### Why Automation Helps

Reduces manual communication work and improves student experience.

---

## 2️⃣ Auto Update Remaining Seats

### Process

Automatically reduce available seats when a student enrolls.

### Why Automation Helps

Maintains accurate seat availability without manual updates.

---

## 3️⃣ Notify Faculty When Course is Full

### Process

Send notification to faculty when course capacity reaches maximum limit.

### Why Automation Helps

Helps faculty manage admissions efficiently.

---

## 4️⃣ Generate Student ID Automatically

### Process

Automatically generate unique student ID during registration.

### Why Automation Helps

Avoids duplicate IDs and saves administrative effort.

---

## 5️⃣ Send Fee Payment Reminder

### Process

Automatically send reminders before fee payment deadline.

### Why Automation Helps

Improves fee collection and reduces missed payments.

---

# 🔀 Flow Design Thinking

## Selected Automation Process

### Auto Email After Student Registration

---

# 📌 Flow Steps

## Trigger

When a new Student record is created.

↓

## Step 1

Capture student details.

↓

## Step 2

Check whether email address exists.

↓

## Decision Point

Is email available?

- Yes → Continue
- No → Stop flow

↓

## Final Action

Send confirmation email to student.

---

# 🔄 Manual vs Automated Process

## Process Chosen

Student Registration Confirmation

---

## Manual Process

- Admin checks registration manually
- Admin writes email manually
- Admin sends confirmation individually

### Problems

- Time consuming
- Human errors
- Delayed communication
- Difficult at large scale

---

## Automated Process Using Salesforce

- Flow triggers automatically after registration
- Confirmation email sent instantly
- No manual effort required

### Improvements

- Faster process
- Better accuracy
- Consistent communication
- Increased productivity

---

# 💡 Reflection

## Why Should Companies Automate Repetitive Business Processes?

Companies should automate repetitive processes because automation:

- Saves time
- Reduces errors
- Improves productivity
- Maintains consistency
- Allows employees to focus on important tasks

Automation helps enterprise systems scale efficiently.

---

# ✍️ Reflective Questions

---

## 1️⃣ Why do companies automate workflows?

Companies automate workflows to improve efficiency, reduce manual effort, and increase productivity.

---

## 2️⃣ What problems happen with manual processes?

Manual processes can cause:

- Human errors
- Delays
- Duplicate work
- Inconsistency

---

## 3️⃣ Difference Between Screen Flow and Record Triggered Flow

| Screen Flow               | Record Triggered Flow  |
| ------------------------- | ---------------------- |
| Requires user interaction | Runs automatically     |
| Uses input screens        | Executes in background |
| Manual input based        | Event based automation |

---

## 4️⃣ Why is no-code automation powerful?

No-code automation allows businesses to automate processes quickly without programming knowledge.

---

## 5️⃣ When should automation be avoided?

Automation should be avoided when:

- Human decision-making is required
- Processes change frequently
- Business logic is unclear

---

## 6️⃣ How does automation improve consistency and productivity?

Automation performs tasks using predefined rules, reducing mistakes and ensuring processes run consistently.

---

# 📚 Trailhead Modules Completed

- Flow Builder Basics
- Data and Actions in Flows

---

# 🎯 Learning Outcome

Learned:

- Salesforce Flow Builder
- Types of Flows
- Business process automation
- Manual vs automated workflows
- No-code automation concepts
- Enterprise workflow management
