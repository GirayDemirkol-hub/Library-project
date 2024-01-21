Library Automation System with Django
Introduction
The Library Automation System is a web-based application developed using the Django framework for the Software Engineering course. The purpose of this system is to streamline and automate various library management processes, providing a user-friendly interface for both librarians and library members.

Features
1. User Authentication
Librarian Login: Librarians can log in securely to access administrative features.
Member Login: Library members can log in to check their borrowing history, renew books, and place holds.
2. Book Management
Add Books: Librarians can add new books to the system, including details such as title, author, genre, and publication date.
Update and Delete Books: Librarians have the ability to update book details or remove books from the catalog.
Search and Filter: Users can search for books based on various criteria like title, author, or genre.
3. Borrowing and Returning Books
Checkout Books: Members can borrow books by checking them out through the system, and librarians can process these transactions.
Return Books: Members can return borrowed books, updating the system's records.
Renewal: Members can request renewals for their borrowed books if the renewal limit has not been reached.
4. Holds and Reservations
Place Holds: Members can place holds on books that are currently checked out.
Notification: Users receive notifications when their requested books become available.
5. User Dashboard
Member Dashboard: Members have a personalized dashboard displaying their borrowing history, holds, and due dates.
Librarian Dashboard: Librarians can view overall library statistics, manage user accounts, and monitor book availability.
Technologies Used
Django: A high-level Python web framework used for rapid development and clean, pragmatic design.
Django REST Framework: Used to build a RESTful API for communication between the frontend and backend.
SQLite: A lightweight relational database management system used for data storage.
The Library Automation System provides an efficient and organized solution for managing library operations. 
Its user-friendly interface enhances the overall library experience for both librarians and members, promoting efficient book management and ensuring a seamless borrowing process. 
The use of Django ensures a scalable and maintainable solution for future improvements and expansions.
