Project overview
This project is a Library Management System that digitizes core library operations such as tracking books, managing different types of users, and monitoring borrowing/return activities. It centralizes all relevant data into a relational database with well-defined entities for books, user categories, transaction statuses, and user statuses.

Core entities
Book: Stores information about each book in the library, such as title, author, category, and availability-related details.

UserType: Defines different categories of users (for example, student, faculty, admin), which can later be used to control borrowing limits, permissions, or access rules.

TxnStatus: Represents the current state of a transaction, such as requested, issued, returned, or overdue, enabling clear tracking of each book loan lifecycle.

UserStatus: Captures the current state of a user account, such as active, blocked, or suspended, helping enforce rules when users have penalties or overdue books.

Main functionality
Enables librarians or admins to add, update, and view book records efficiently.

Differentiates user behavior and permissions through UserType, supporting role-based rules and policies.

Uses TxnStatus to maintain a clear history and current state of each issue/return transaction, reducing confusion and manual errors.

Uses UserStatus to control access for users with violations, ensuring only eligible users can initiate new transactions.
