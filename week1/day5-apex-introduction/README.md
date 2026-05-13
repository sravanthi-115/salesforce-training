# Day 5 - Introduction to Apex

---

# 📌 What is Apex?

Apex is Salesforce’s programming language used to implement custom business logic and backend processing.

It is similar to Java and is specially designed for the Salesforce platform.

Apex allows developers to:

- Write custom logic
- Perform database operations
- Automate complex business processes
- Integrate external systems
- Handle advanced validations

---

# 💡 Why Apex Is Needed

Salesforce provides many no-code tools like:

- Flow Builder
- Validation Rules
- Formula Fields

However, some enterprise requirements become too complex for declarative tools alone.

Apex helps solve:

- Complex calculations
- Advanced automation
- External integrations
- Custom business workflows

---

# 🔄 Difference Between Flow and Apex

| Flow                         | Apex                            |
| ---------------------------- | ------------------------------- |
| No-code automation           | Programming-based solution      |
| Easier to build              | Requires coding knowledge       |
| Best for simple automation   | Best for complex business logic |
| Built using visual interface | Written using Apex syntax       |
| Faster development           | More flexible and powerful      |

---

# ⚙️ Difference Between Configuration and Coding

| Configuration                    | Coding                             |
| -------------------------------- | ---------------------------------- |
| Uses clicks and setup tools      | Uses programming language          |
| Faster implementation            | More customizable                  |
| Less technical                   | Requires development skills        |
| Suitable for simple requirements | Suitable for advanced requirements |

---

# 💻 Real Examples Where Apex Is Needed

---

## 1️⃣ Complex Fee Calculation

### Example

Calculate fees based on:

- Scholarship
- Attendance
- Course type
- Hostel facility

### Why Flow Is Not Enough

Business logic becomes too complex and requires programming.

---

## 2️⃣ Integration with External Payment Gateway

### Example

Connect Salesforce with online payment systems.

### Why Apex Is Needed

External API integrations require custom code.

---

## 3️⃣ Advanced Student Eligibility Logic

### Example

Allow course registration only if:

- Attendance > 75%
- No pending fees
- Prerequisite courses completed

### Why Apex Is Needed

Complex conditional processing requires programming logic.

---

# 🎓 College Management System Integration

---

# 📌 CRM Concept

The College Management System manages:

- Students
- Courses
- Faculty
- Admissions
- Notifications

The system helps automate and organize academic processes efficiently.

---

# 📂 Objects Used

## Custom Objects

- Student
- Faculty
- Course
- Department

## Standard Objects

- Account
- Contact

---

# 🔗 Relationships

| Parent Object | Child Object | Relationship |
| ------------- | ------------ | ------------ |
| Department    | Course       | Lookup       |
| Department    | Faculty      | Lookup       |
| Course        | Student      | Lookup       |

Relationships help connect related academic data.

---

# ✅ Validation Rules

## Example 1

Student email cannot be empty.

### Purpose

Prevents incomplete student records.

---

## Example 2

Student age must be greater than zero.

### Purpose

Prevents invalid age values.

---

## Example 3

Filled seats cannot exceed total seats.

### Purpose

Avoids overbooking courses.

---

# 🧮 Formula Fields

## Remaining Seats Formula

Total Seats - Filled Seats

### Purpose

Automatically calculates available course seats.

---

## Percentage Formula

(Obtained Marks / Total Marks) \* 100

### Purpose

Automatically calculates student percentage.

---

# 🔄 Flow Automation

## Auto Email Notification

### Process

When a student registers:

- Flow triggers automatically
- Confirmation email is sent

### Benefit

Improves communication and reduces manual work.

---

# 🧠 Pseudocode Examples

---

## Example 1

```text
IF seats are full
THEN block student registration
```

---

## Example 2

```text
IF attendance < 75%
THEN notify student
```

---

## Example 3

```text
IF fee payment is pending
THEN restrict exam hall ticket generation
```

---

# 💡 Reflection

## Why Can’t All Enterprise Logic Be Built Using Only Clicks and Configuration?

Enterprise systems often contain:

- Complex workflows
- Advanced calculations
- External integrations
- Large-scale processing
- Dynamic business rules

No-code tools are excellent for simple automation, but advanced enterprise requirements eventually need programming for flexibility and scalability.

Apex provides:

- Greater control
- Advanced customization
- Powerful business logic implementation

---

# ✍️ Reflective Questions

---

## 1️⃣ Why is Apex needed if Salesforce already has Flows?

Flows are useful for simple automation, but Apex is needed for advanced business logic and integrations.

---

## 2️⃣ When should developers prefer no-code solutions?

Developers should prefer no-code solutions when requirements are simple, maintainable, and achievable using standard Salesforce tools.

---

## 3️⃣ What problems require custom programming?

Problems involving:

- Complex calculations
- External systems
- Advanced validations
- Large data processing

require custom programming.

---

## 4️⃣ Why is business logic important in enterprise systems?

Business logic ensures processes follow company rules and workflows correctly.

---

## 5️⃣ Why should developers avoid unnecessary coding?

Unnecessary coding increases:

- Complexity
- Maintenance effort
- Development time

Declarative solutions should be preferred whenever possible.

---

## 6️⃣ How does programming increase flexibility?

Programming allows developers to create advanced custom solutions beyond standard platform limitations.

---

# 📚 Trailhead Modules Completed

- Apex & .NET Basics
- Apex Basics & Database

---

# 🎯 Learning Outcome

Learned:

- Basics of Apex programming
- Difference between Flow and Apex
- Declarative vs programmatic development
- Business logic implementation
- Enterprise customization concepts
