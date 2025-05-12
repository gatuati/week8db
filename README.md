# Library Management System Database

## Project Description
This is a complete MySQL database implementation for a Library Management System. The database tracks books, authors, publishers, library members, loans, reservations, and fines. It's designed to support all core operations of a modern library.

## Features
- Comprehensive book tracking with ISBN support
- Member management with different membership types
- Loan tracking with due dates and late fee calculations
- Reservation system for high-demand books
- Publisher and author information management
- Staff management
- Audit logging for all system changes

## How to Setup
1. Ensure you have MySQL installed (XAMPP includes MySQL)
2. Open phpMyAdmin or MySQL command line
3. Create a new database or use an existing one
4. Import the `Library_management_system.sql` file
5. The database will be ready for use

## ERD Diagram
![ERD library_management](https://github.com/user-attachments/assets/f474669e-09ec-4888-afa3-6c0570cc01b3)



## Tables Overview
1. **Members** - Library member information
2. **Publishers** - Book publisher details
3. **Authors** - Author information
4. **Books** - Main book catalog
5. **BookAuthors** - Many-to-many relationship between books and authors
6. **Loans** - Book lending transactions
7. **Fines** - Late return or lost book fines
8. **Reservations** - Book reservation system
9. **Staff** - Library staff information
10. **AuditLog** - System change tracking

## Constraints
The database includes:
- Primary and foreign keys
- Unique constraints
- Check constraints for data validation
- Default values
- Indexes for performance optimization
