 Salesforce Summer Program – Day 3

 Data Modeling in Salesforce

 Difference Between App, Object, Record, and Field

In Salesforce, an app is a collection of tabs, objects, and tools used for a specific purpose. For example, the Sales app is used to manage customer and sales information.

An object is similar to a table in a database. It stores related information. For example, the Contact object stores customer details.

A record is a single entry inside an object. For example, one student’s details inside the Student object is considered a record.

A field is used to store a particular piece of information in a record. Examples are Name, Email, Phone Number, and Address.


Standard Objects vs Custom Objects

Standard objects are already available in Salesforce by default. These are commonly used objects such as Account, Contact, Opportunity, and Lead.

Custom objects are created according to business needs. They are not available by default and can be designed based on requirements. Examples include Student, Course, Faculty, and Admission.

Standard objects are mainly used for general CRM activities, while custom objects are useful for organization-specific processes.



College Data Model

For the college management system, the following objects can be used:

* Student
* Course
* Faculty
* Admission

Relationships

* A student can enroll in a course.
* A faculty member can teach multiple courses.
* An admission record is connected to a student.

This data model helps in organizing information properly and maintaining relationships between different records.

Diagram

(Add schema builder screenshot or diagram here)



Formula Fields

Formula fields are used to calculate values automatically using formulas.

One example is the Days Remaining field.

Formula:
EndDate - TODAY()

This formula calculates the remaining number of days before the contract expires.

Another example is calculating total fees by adding tuition fees and hostel fees.

Formula fields help reduce manual work and improve accuracy.

Validation Rules

Validation rules are used to prevent users from entering incorrect or incomplete data.

One example is validating that the contact ZIP code matches the account ZIP code.

Another example is making the phone number field mandatory.

Validation rules help maintain proper and consistent data inside Salesforce.



Reflection

Structured enterprise data is important because it helps organizations store and manage information in a proper way. It improves data accuracy, avoids duplicate records, and helps employees access information easily.

In Salesforce, structured data is useful for reports, dashboards, automation, and maintaining relationships between objects. Proper data modeling makes business processes easier and more efficient.



What I Learned

* Difference between apps, objects, records, and fields
* Standard and custom objects
* Data modeling basics
* Relationships between objects
* Formula fields
* Validation rules
* Importance of structured data

Screenshots

<img width="1477" height="882" alt="WhatsApp Image 2026-05-11 at 7 42 34 PM" src="https://github.com/user-attachments/assets/43c009db-4363-4d61-862e-d57fdb15a886" />
<img width="1599" height="761" alt="WhatsApp Image 2026-05-11 at 7 40 52 PM" src="https://github.com/user-attachments/assets/e44d6717-d530-4978-80dd-2fd435c735b7" />
<img width="1600" height="651" alt="WhatsApp Image 2026-05-11 at 7 39 02 PM" src="https://github.com/user-attachments/assets/25ac74d7-a3bf-4b3a-a242-cb8133fa3734" />
<img width="919" height="580" alt="WhatsApp Image 2026-05-11 at 7 38 41 PM" src="https://github.com/user-attachments/assets/c13eb2cc-8e13-41d7-9e2e-d3d8f020cf26" />
<img width="1600" height="704" alt="WhatsApp Image 2026-05-11 at 7 38 17 PM" src="https://github.com/user-attachments/assets/08df3d33-0c13-435b-acfd-06eca14417ce" />

