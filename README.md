# Library Madani  

**A Secure Library Management System**  
Library Madani is a web-based library management system designed to provide a seamless and secure experience for users. The system incorporates advanced security features, including secure authentication and protection against SQL injection attacks.  

---

## Features  
### User Features  
- **Book Catalog:** Browse books by category, author, or title.  
- **User Accounts:** Create and manage user profiles with secure authentication.  
- **Borrowing System:** View and manage borrowed books with due dates and history.  

### Admin Features  
- **Book Management:** Add, update, and remove books in the catalog.  
- **User Management:** Manage user accounts, including roles and permissions.  
- **Reports:** Generate reports for borrowed and available books.  

### Security Features  
- **Secure Authentication:**  
  - Implements password hashing using bcrypt for safe storage.  
  - User roles with access control for admins and general users.  
- **SQL Injection Protection:**  
  - Uses prepared statements to prevent malicious SQL inputs.  
  - Input validation for all user-provided data.  

---

## Technologies Used  
- **Frontend:** HTML, CSS, JavaScript (Bootstrap for responsive design)  
- **Backend:** PHP (Laravel Framework or Native PHP)  
- **Database:** MySQL  
- **Security:** bcrypt (Password Hashing), PDO (SQL Injection Protection)  

---

## Screenshots  

### Home Page  
The main interface where users can browse the library catalog.  
![Home Page](https://github.com/user-attachments/assets/home-page-placeholder.jpg)  

### Book Catalog  
Explore books with filtering and search functionality.  
![Book Catalog](https://github.com/user-attachments/assets/book-catalog-placeholder.jpg)  

### Admin Dashboard  
Manage books, users, and view system reports.  
![Admin Dashboard](https://github.com/user-attachments/assets/admin-dashboard-placeholder.jpg)  

### Secure Login Page  
User login with secure authentication and access control.  
![Login Page](https://github.com/user-attachments/assets/login-page-placeholder.jpg)  

---

## Installation  
1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/library-madani.git
