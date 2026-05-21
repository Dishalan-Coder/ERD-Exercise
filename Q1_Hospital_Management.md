# Question 1 — Hospital Management System (Healthcare Industry)

## Scenario

A private hospital wants to build a database system to manage its day-to-day operations. The hospital has multiple departments (e.g., Cardiology, Neurology, Orthopedics). Each department has many doctors assigned to it, but a doctor belongs to only one department.

Patients visit the hospital and are assigned to a doctor. A patient can be treated by multiple doctors over time, and a doctor can treat many patients. Each visit is recorded with the visit date, diagnosis, and prescribed treatment.

The hospital also maintains a list of medicines. Each prescription issued during a visit can include one or more medicines, and each medicine can appear in many prescriptions. The quantity prescribed for each medicine per prescription must also be stored.

Rooms are available in the hospital for admitted patients. A patient can be admitted to one room at a time, but a room can admit different patients over different time periods (admission date and discharge date must be stored).

---

## Your Task

Draw a complete **Entity-Relationship (ER) Diagram** for the above system.

### Requirements

1. Identify all **entities** from the scenario.
2. Define the **attributes** for each entity (underline the primary key).
3. Identify all **relationships** between entities.
4. Specify the **cardinality** (1:1, 1:N, M:N) for each relationship.
5. Identify any **weak entities** if applicable.
6. For M:N relationships, identify the **relationship attributes**.

---

## Hints

| Entity (Suggested) | Key Attributes (Suggested) |
|--------------------|---------------------------|
| Department | DeptID, DeptName, Location |
| Doctor | DoctorID, Name, Specialization, Phone |
| Patient | PatientID, Name, DOB, Gender, Address |
| Visit | VisitID, VisitDate, Diagnosis, Treatment |
| Medicine | MedicineID, MedicineName, Category, UnitPrice |
| Room | RoomID, RoomType, Floor |

> Note: These are only hints. You may add or modify attributes as you see fit.

---

## Marking Criteria

| Criteria | Marks |
|----------|-------|
| Correct entities identified | 10 |
| Correct attributes with primary keys | 10 |
| Correct relationships & cardinality | 15 |
| Weak entities / relationship attributes | 10 |
| Diagram clarity and notation | 5 |
| **Total** | **50** |
