# Day 3 - Data Modeling in Salesforce

---

# 📌 What is Data Modeling?

Data Modeling is the process of organizing and structuring business data in a proper format so that applications can store, retrieve, and manage information efficiently.

Salesforce uses objects, fields, records, and relationships to model business systems.

---

# 📘 Difference Between App, Object, Record, and Field

| Concept | Description                                | Example                |
| ------- | ------------------------------------------ | ---------------------- |
| App     | Collection of related features and objects | College Management App |
| Object  | Database table used to store data          | Student Object         |
| Record  | Single row/data entry inside an object     | One student’s details  |
| Field   | Individual data attribute                  | Student Name, Age      |

---

# 📘 Standard vs Custom Objects

## Standard Objects

Standard objects are pre-built objects provided by Salesforce.

### Examples

- Account
- Contact
- Opportunity
- Lead

These are commonly used CRM objects.

---

## Custom Objects

Custom objects are created by developers or admins based on business requirements.

### Examples

- Student
- Faculty
- Course
- Department

Custom objects help organizations build domain-specific applications.

---

# 🎓 College Management System Data Model

## Objects Used

### Custom Objects

- Student
- Faculty
- Course
- Department

### Standard Objects

- Account
- Contact

---

# 🔗 Relationships Between Objects

| Parent Object | Child Object | Relationship Type   |
| ------------- | ------------ | ------------------- |
| Department    | Faculty      | Lookup Relationship |
| Department    | Course       | Lookup Relationship |
| Course        | Student      | Lookup Relationship |
| Faculty       | Course       | Lookup Relationship |

---

# 📌 Why Relationships Are Important

Relationships help connect related business data.

Benefits:

- Avoid duplicate data
- Maintain structured records
- Improve reporting
- Enable real-world business workflows

Example:
A student belongs to a course, and a course belongs to a department.

---

# 🧮 Formula Fields

Formula Fields automatically calculate values based on logic.

---

## 1. Full Name Formula

### Formula Field

First Name + Last Name

### Why should this be calculated automatically?

Automatically generates full name and avoids manual entry errors.

---

## 2. Remaining Seats

### Formula Field

Total Seats - Filled Seats

### Why should this be calculated automatically?

Helps users instantly know available seats in a course.

---

## 3. Percentage Calculation

### Formula Field

(Obtained Marks / Total Marks) \* 100

### Why should this be calculated automatically?

Automatically calculates student percentage accurately.

---

# ✅ Validation Rules

Validation Rules prevent invalid or incorrect data from being saved.

---

## 1. Email Cannot Be Empty

### Rule

Student email field must contain a value.

### Problem Prevented

Avoids incomplete student records.

---

## 2. Student Age Cannot Be Negative

### Rule

Age must be greater than zero.

### Problem Prevented

Prevents invalid age values.

---

## 3. Course Seats Cannot Exceed Limit

### Rule

Filled seats should not exceed total seat capacity.

### Problem Prevented

Avoids overbooking courses.

---

# 💡 Reflection

## Why Do Companies Need Structured Data Instead of Random Spreadsheets?

Companies need structured data because:

- Data becomes easier to manage
- Relationships between records can be maintained
- Reporting becomes accurate
- Automation becomes possible
- Duplicate and inconsistent data can be reduced

Random spreadsheets often create:

- Data inconsistency
- Duplicate entries
- Difficult reporting
- Poor scalability

Enterprise systems require centralized and structured data management.

---

# ✍️ Reflective Questions

## 1. Why can’t companies manage everything using Excel sheets?

Excel sheets become difficult to manage when data grows large. They also create duplication, inconsistency, and reporting problems.

---

## 2. Why are relationships important between objects?

Relationships connect related business data and help organizations maintain structured systems.

---

## 3. What problems happen if data is inconsistent?

Inconsistent data leads to incorrect reports, duplicate records, poor decision-making, and operational issues.

---

## 4. Why should repetitive calculations be automated?

Automation saves time, reduces human error, and improves accuracy.

---

## 5. Why should invalid data be blocked early?

Blocking invalid data improves data quality and prevents future business problems.

---

## 6. Why is Salesforce called a metadata-driven platform?

Salesforce is metadata-driven because applications can be customized using configurations, objects, fields, and rules without changing core system code.

---

# 📚 Trailhead Modules Completed

- Data Modeling
- Formulas and Validations

---

# 🎯 Learning Outcome

Learned:

- Salesforce data modeling concepts
- Objects, fields, and records
- Relationships between objects
- Formula Fields
- Validation Rules
- Importance of structured enterprise data
