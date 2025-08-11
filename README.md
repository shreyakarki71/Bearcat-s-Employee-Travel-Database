# BearcatWealth Travel & Expense Management Database

This project designs and implements a **centralized SQL database** for BearcatWealth, a finance firm with extensive client-facing travel needs across the US. The system streamlines **travel requests, expense tracking, policy compliance, and vendor management**, replacing the firm’s manual and inefficient reporting process.

## Business Context
BearcatWealth employees frequently travel to meet clients, host lunches, and attend conferences. Managing these expenses manually led to:
- Delayed reimbursements
- Lost receipts
- Weak policy enforcement
- Overspending due to unclear budgets
- Vendor payment reconciliation issues

## Project Objectives
- Build a **normalized relational database** to store and manage all travel & expense records
- Ensure **policy compliance** through automated checks
- Provide **real-time budget tracking**
- Streamline **vendor and payment management**
- Support **transparent approvals** and faster reimbursements

## Features Implemented
- **ERD Design** – entity relationships for employees, trips, approvals, expenses, vendors, departments, and corporate cards
- **Normalization** – up to 3NF to remove redundancy and maintain data integrity
- **Database Schema** – creation of tables with primary/foreign keys, constraints, and indexes
- **Sample Data Population** – INSERT statements for realistic demo data
- **Query Scripts** – reports for budget tracking, top vendors, spend by category, and policy compliance
- **Policy Enforcement** – max allowable spend per category (travel, meals, transportation) checked via queries

## Files in Repository
- `erd_diagram.png` – Entity Relationship Diagram  
- `normalization_steps.pdf` – Normalization documentation   
- `sample_data.sql` – Test dataset (DML)  
- `queries.sql` – Analytical and operational queries  
- `BearcatWealth_ Final Report .pdf` – Full project summary with business case, solution, and insights  

## Example Reports
- Total spend by department
- Pending vs. approved travel requests
- Expenses exceeding policy limits
- Vendor payment summaries
- Average trip cost & duration

## Technologies Used
- SQL (MySQL / PostgreSQL / SQLite/ ACCESS SQL)
- Lucidchart / Draw.io for ERD
- Microsoft Excel / Google Sheets for initial dataset cleanup




