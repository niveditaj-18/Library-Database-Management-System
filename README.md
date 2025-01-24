# Library-Database-Management-System
A project implementing a database management system for a public library. This project includes database design, implementation, querying, and reporting to manage library resources, track borrowing activity, and generate actionable insights for library staff.

## Overview
This project implements a database management system for a public library. The system facilitates:
- Management of library resources (books, e-books, magazines, and audiobooks).
- Tracking borrowing activity and generating analytics reports.
- Automating alerts for overdue materials and membership management.

## Features
1. **Materials Management**: Store details of library materials, including titles, authors, genres, and publication dates.
2. **Membership Management**: Maintain member records, borrowing history, and contact details.
3. **Borrowing Activity**: Track borrowing and returning of materials with due dates and overdue alerts.
4. **Reporting**: Generate reports on library usage and popular materials.

## Dataset
- **Files**:
  - Borrow.csv
  - Genre.csv
  - Catalog.csv
  - Authorship.csv
  - Author.csv
  - Material.csv
  - Staff.csv
  - Member.csv
- **Description**: The dataset includes library materials, members, borrowing records, and genres.

## Methodology
1. **Database Design**:
   - ER Diagram for defining entities and relationships.
   - Normalization to minimize redundancy and ensure data integrity.
2. **Database Implementation**:
   - PostgreSQL for database schema and sample data insertion.
3. **Queries**:
   - SQL scripts for data retrieval, updates, and analytics.
4. **Automation**:
   - Triggers to send overdue alerts and manage memberships.

## Tools and Technologies
- **Database**: PostgreSQL
- **ER Diagram Tool**: Lucidchart or Draw.io
- **Languages**: SQL

