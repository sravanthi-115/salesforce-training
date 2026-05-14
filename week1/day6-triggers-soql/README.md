# Day 6 - SOQL and Apex Triggers

---

# 📌 What is SOQL?

SOQL (Salesforce Object Query Language) is a query language used to retrieve data from Salesforce objects.

It is similar to SQL but specifically designed for Salesforce data.

SOQL helps developers:

- Retrieve records
- Filter data
- Search related records
- Generate reports
- Process business data

---

# 📌 What is SOSL?

SOSL (Salesforce Object Search Language) is used to search text across multiple Salesforce objects at the same time.

### Example Use Cases

- Search student by name
- Search course information
- Search faculty records

---

# 📌 What are DML Operations?

DML (Data Manipulation Language) operations are used to modify Salesforce records.

### Common DML Operations

- Insert
- Update
- Delete
- Upsert

These operations help applications manage business data.

---

# 📌 What is an Apex Trigger?

An Apex Trigger is a piece of Apex code that executes automatically when specific events happen on Salesforce records.

Triggers help automate event-driven business logic.

### Trigger Events

- Before Insert
- After Insert
- Before Update
- After Update
- Before Delete
- After Delete

---

# 🔄 Difference Between Flow and Trigger

| Flow                          | Apex Trigger               |
| ----------------------------- | -------------------------- |
| No-code automation            | Code-based automation      |
| Easier to build               | Requires programming       |
| Suitable for simple workflows | Suitable for complex logic |
| Visual configuration          | Written in Apex            |
| Faster implementation         | More powerful and flexible |

---

# 🔄 Difference Between Before Trigger and After Trigger

| Before Trigger                     | After Trigger               |
| ---------------------------------- | --------------------------- |
| Runs before record is saved        | Runs after record is saved  |
| Used for validations and updates   | Used for actions after save |
| Modifies record data before saving | Performs post-save actions  |
| Example: Validate attendance       | Example: Send notification  |

---

# 🎓 Trigger Use Cases for College Management System

---

## 1️⃣ After Student Registration → Send Welcome Email

### Trigger Event

After Insert on Student Object

### Purpose

Automatically welcome newly registered students.

---

## 2️⃣ After Course Becomes Full → Notify Faculty

### Trigger Event

After Update on Course Object

### Purpose

Notify faculty when course capacity reaches maximum limit.

---

## 3️⃣ After Attendance Drops Below 75% → Send Warning

### Trigger Event

After Update on Student Attendance

### Purpose

Warn students about attendance shortage.

---

## 4️⃣ After Fee Payment → Generate Receipt

### Trigger Event

After Update on Payment Record

### Purpose

Automatically generate payment confirmation.

---

## 5️⃣ After Exam Result Published → Notify Students

### Trigger Event

After Insert on Result Object

### Purpose

Inform students that results are available.

---

# ⚖️ Flow vs Trigger Thinking

| Use Case                            | Recommended Solution | Reason                      |
| ----------------------------------- | -------------------- | --------------------------- |
| Simple email notification           | Flow                 | Easy no-code automation     |
| Complex fee eligibility calculation | Apex Trigger         | Requires advanced logic     |
| Updating related records            | Flow                 | Can be handled visually     |
| External payment API integration    | Apex Trigger         | Requires custom programming |

---

# 🔍 Query Thinking Examples

---

## Student Queries

- Find all students in Course A
- Find students with attendance below 75%
- Find students who have pending fees

---

## Course Queries

- Find courses with available seats
- Find courses handled by Faculty X
- Find courses under Computer Science Department

---

## Faculty Queries

- Find all faculty members in a department
- Find faculty handling more than two courses
- Find faculty contact details

---

# 💡 Reflection

## Why Do Enterprise Systems Need Event-Driven Behavior?

Enterprise systems manage large amounts of real-time business data.

Event-driven behavior helps systems:

- React automatically to changes
- Reduce manual work
- Improve response speed
- Maintain process consistency
- Improve business efficiency

Examples:

- Sending notifications automatically
- Updating records instantly
- Triggering workflows after data changes

Without event-driven systems, businesses would rely heavily on manual operations.

---

# ✍️ Reflective Questions

---

## 1️⃣ Why do systems need triggers?

Triggers help systems automatically respond to business events and data changes.

---

## 2️⃣ Difference Between Polling and Event-Driven Systems

| Polling System                  | Event-Driven System           |
| ------------------------------- | ----------------------------- |
| Continuously checks for changes | Reacts only when events occur |
| More resource usage             | More efficient                |
| Slower response                 | Faster automation             |

---

## 3️⃣ Why are database queries important?

Queries help retrieve required business data efficiently from large databases.

---

## 4️⃣ When should Flows be preferred over Triggers?

Flows should be preferred for simple automation tasks that do not require complex programming logic.

---

## 5️⃣ What problems happen if automation logic becomes too complex?

Complex automation can become difficult to maintain, debug, and scale.

---

## 6️⃣ Why should developers think carefully before automating actions?

Poor automation design can create:

- Incorrect data updates
- Performance issues
- Unnecessary complexity

Automation should solve real business problems efficiently.

---

# 📚 Trailhead Modules Completed

- Database & .NET Basics
- Apex Triggers

---

# 🎯 Learning Outcome

Learned:

- Basics of SOQL and SOSL
- DML operations
- Apex Triggers
- Event-driven systems
- Flow vs Trigger concepts
- Enterprise automation logic
