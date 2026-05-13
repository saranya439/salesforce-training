# Day 5 - Apex Introduction

## 1. What is Apex?

Apex is a strongly typed, object-oriented programming language developed by Salesforce. It is used to execute flow and transaction control statements on Salesforce servers along with calls to APIs.

Apex helps developers:
1. Create custom business logic
2. Automate processes
3. Perform database operations
4. Integrate external systems
5. Build enterprise-level applications

Example:
```apex
Account acc = new Account(Name='ABC Company');
insert acc;
```

---

# 2. Difference Between Technologies

## Flow vs Apex

| Flow | Apex |
|------|------|
| No-code/Low-code automation | Programming language |
| Easy to build using drag-and-drop | Requires coding knowledge |
| Best for simple automation | Best for complex logic |
| Faster development | More flexible and powerful |
| Limited customization | Full customization possible |

### Example
- Flow: Send email when student record is created
- Apex: Complex attendance calculation with conditions

---

## Configuration vs Coding

| Configuration | Coding |
|--------------|--------|
| Uses clicks not code | Uses programming |
| Faster implementation | More development time |
| Limited functionality | Unlimited customization |
| Easier maintenance | Requires developer skills |
| Used for standard business processes | Used for advanced requirements |

### Example
- Configuration: Validation Rule
- Coding: Custom Apex Trigger

---

# 3. Real Examples Where Apex Is Needed

## Example 1: Automatic Fee Reminder
When a student's fee due date is near, Apex sends automatic reminders through email.

## Example 2: Attendance Processing
Apex calculates attendance percentage and marks students as eligible or detained.

## Example 3: External Payment Integration
Apex connects Salesforce with online payment systems to update fee payment status automatically.

---

# 4. Integrated System Design

## College Management System

### CRM
Salesforce CRM is used to manage:
- Students
- Faculty
- Courses
- Fees
- Attendance
- Placements

---

## Objects

### Standard Objects
- Account
- Contact

### Custom Objects
- Student
- Course
- Attendance
- Fee
- Placement

---

## Relationships

| Object 1 | Relationship | Object 2 |
|----------|--------------|----------|
| Student | Enrolled In | Course |
| Student | Has | Attendance |
| Student | Pays | Fee |
| Student | Gets | Placement |

---

## Validation

Validation Rules ensure:
- Student ID cannot be empty
- Fee amount must be positive
- Attendance percentage cannot exceed 100
- Phone numbers must contain valid digits

---

## Flow

Flows are used for:
- Sending admission confirmation emails
- Updating attendance automatically
- Creating fee reminders
- Approving leave requests

---

## Apex

Apex is used for:
- Complex attendance calculations
- Integration with external systems
- Automatic scholarship eligibility calculation
- Bulk student data processing

---

# 5. Pseudocode Examples

## Example 1: Attendance Calculation

```text
START
Input total classes
Input attended classes
Calculate percentage
IF percentage < 75
   Mark student as detained
ELSE
   Mark student as eligible
END
```

---

## Example 2: Fee Payment Check

```text
START
Check due date
IF payment not completed
   Send reminder email
ELSE
   Update payment status
END
```

---

## Example 3: Placement Eligibility

```text
START
Check CGPA
Check attendance
IF CGPA > 7 AND attendance > 75
   Eligible for placement
ELSE
   Not eligible
END
```

---

# 6. Reflection

Enterprise systems eventually need programming because business requirements become more complex over time.

Configuration and automation tools are useful for simple tasks, but large organizations require:
- Advanced business logic
- System integrations
- Security controls
- Bulk data processing
- Real-time automation

Programming languages like Apex provide flexibility and scalability to handle these complex enterprise requirements efficiently.

---

# Conclusion

Apex plays an important role in Salesforce development by enabling advanced automation, integrations, and customized enterprise solutions. It helps organizations build scalable and intelligent systems beyond basic configuration features.

# Screenshots:
