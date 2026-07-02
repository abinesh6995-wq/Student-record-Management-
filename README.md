# Student Record Management System

A menu-driven C mini project that manages student records (Roll Number, Name, Percentage) using a **singly linked list**, with file persistence, search, modify, delete, and sort operations.

## Features

- **Add Record** — dynamically creates a new node and appends it to the linked list. Roll numbers are auto-assigned as the smallest available positive integer, with no duplicates.
- **Delete Record** — delete by Roll Number (direct) or by Name (shows matches, then asks for the Roll Number to confirm).
- **Show Records** — displays all records in a formatted table.
- **Modify Record** — search by Roll Number, Name, or Percentage, then update the Name and/or Percentage of the selected record.
- **Save Records** — writes all records to `student.dat`; data is auto-loaded from `student.dat` on startup.
- **Sort Records** — sort the linked list by Name or by Percentage.
- **Exit** — choose to save before exiting or exit without saving.
