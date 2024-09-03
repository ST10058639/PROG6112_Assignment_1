# Project Overview

## Unit Tests
All unit tests have been completed and are stored in the `test` packages folders.

---

## Question One: ABC College - Student Management Application

This application allows ABC College to manage student information effectively. Below is an overview of its features:

### Application Features:
- **Welcome Screen:** Upon launching the application, users are greeted with a welcome message and prompted to either access the main menu or quit the application.
- **Main Menu Options:**
  - **Add New Student:** Allows the user to input and save a new student's information.
  - **Search Student by ID:** Enables the user to search for a specific student using their ID.
  - **Delete Student:** Provides an option to remove a student’s information from the system.
  - **Generate Student Report:** Compiles and displays a report of all students.
  - **Export Student List:** Users can export the list of students to a CSV file onto their desktop for external use.
  - **Exit Application:** Allows the user to safely exit the application.
- **User Interaction:** The application uses a `Scanner` to read the user's input and perform the corresponding action.
- **Data Storage:** Student data is stored in an `ArrayList`, which is temporary and only available while the program is running. All data is lost when the program stops.
- **Looped Menu:** The main menu is continuously displayed until the user opts to exit the application.

---

## Question Two: Electricity Bill Generation Application

This Java application manages and calculates electricity bills for customers, incorporating various object-oriented programming principles.

### Application Features:
- **Customer Bill Management:**
  - **Input Customer Details:** Users can enter details for each customer.
  - **Calculate Updated Bills:** The application computes and updates the electricity bills for each customer.
  - **Generate Summary Report:** A summary report of all customer bills can be created.
- **OOP Concepts:**
  - **Inheritance:** The `CustomerBill` class extends the `GenerateBill` class.
  - **Polymorphism:** The `GenerateBill` class implements the `iCustomer` interface.
  - **Encapsulation:** The classes encapsulate and provide controlled access to customer data.
  - **Abstraction:** The `iCustomer` interface defines common behaviors for customers, which are implemented by the `GenerateBill` class.
- **Data Storage:** Customer bills are stored in an `ArrayList`, with each entry representing an individual customer's bill.
- **User Interface:** The `RunApplication` class serves as the user interface, allowing users to enter customer details, calculate bills, and generate reports.

