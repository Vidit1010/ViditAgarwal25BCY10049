Financial Expense Manager

An object-oriented desktop application built with Python to help users track, organize, and gain insights into their personal spending for effective financial planning.


---

The Problem & Our Solution

The Challenge

Most people struggle to accurately track where their money goes each month. Without clear visibility into spending patterns, budgeting relies on guesswork, which often leads to overspending
The Solution

We developed a simple desktop application that addresses this through:

1. Recording every expense


2. Organizing expenses by category (e.g., food, transportation, entertainment)


3. Providing a clean summary view that shows exactly how much is being spent in each category
Technologies & Architecture

Programming Stack

The application is built using a robust and familiar set of technologies:

Component	Technology	Role

Language	Python	Primary programming language using Object-Oriented Design
Database	SQLite	Efficient local data storage
Interface	Tkinter	Used to create the desktop GUI



---

System Architecture

The system is modular, ensuring maintainability and scalability:

Input Module – Handles form-based entry of new expenses

Storage Module – Manages the SQLite database operations

Report Module – Provides data analysis and visualization (charts, summaries)
UI Module – Presents a user-friendly dashboard for interaction and viewing data


Core Process Flow

User enters expense → App validates data → Assigns category → Saves to database → Updates summary → User views analytics


---

Key Features

Real-Time Tracking – Instantly see how money is spent

Category Organization – Expenses automatically grouped

Custom Categories – Create personalized categories

Detailed Reports – Category-wise breakdown, monthly totals, insights

Validation Checks – Prevent invalid inputs and errors

UI Module – Presents a user-friendly dashboard for interaction and viewing data


Core Process Flow

User enters expense → App validates data → Assigns category → Saves to database → Updates summary → User views analytics


---

Challenges Overcome

Database Synchronization

Issue: Data wasn’t saving when the app closed

Solution: Added proper SQLite connection handling and auto-commit


Category Logic

Issue: Certain expenses didn’t match default categories

Solution: Introduced custom category creation
---

Future Vision

Planned enhancements:

Complete Reports Module – Add charts, graphs, and analytics dashboards

Mobile Integration – Let users log expenses from a smartphone

Cloud Sync – Sync data across multiple devices

Smart Recommendations – AI-powered tips for better budgeting



---

Team Members

Janamjay Gupta (Reg. No. 25BAI11262)

Sayan Manna (Reg. No. 25BAI10467)

Ganesh S (Reg. No. 25MEI10020)

Vidit Agarwal (Reg. No. 25BCY10049)

Rochan R K (Reg. No. 25BCE11177)
