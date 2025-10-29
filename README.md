# 📚 LibraTrack

## 📖 Description / Overview
The **LibraTrack System** is a web-based application designed to streamline the management of books, borrowers, and borrowing records. It allows librarians to efficiently track available books, register new borrowers, and record which books have been borrowed, all within a user-friendly interface.

---

## 🎯 Objectives
- To develop a system for organizing and managing library resources.  
- To enable the recording of borrower information and borrowed books.  
- To simplify library operations through a centralized database and CRUD functionalities.  

---

## ⚙️ Features / Functionality
- 📖 **Book Management** — Add, edit, delete, and view books with details such as title, author, genre, and year published.  
- 🧍‍♂️ **Borrower Management** — Register borrowers and track what books they have borrowed.  
- 🔗 **Book-Borrower Linking** — View which books are currently borrowed and by whom.  
- 💾 **Database Integration** — Stores all data using Laravel and MySQL for secure and reliable management.  
- 🖥️ **Responsive Interface** — Built using Laravel Blade templates with Bootstrap for a clean, modern look.  

---

## ⚙️ Installation Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/smsnjr7/MidtermExam

Navigate to the project folder:
- cd MidtermExam

Install dependencies using Composer:
- composer install

Copy the environment file and configure it:
- cp .env.example .env
- Then, edit your .env file to include your database credentials.

Generate the application key:
- php artisan key:generate

Run database migrations:
- php artisan migrate

Start the development server:
- php artisan serve


Your app will now run at http://127.0.0.1:8000/


## 🚀 Usage

Open your browser and go to:
http://127.0.0.1:8000/

- Use the navigation to manage Books, Borrowers, and Borrowing Records.

- Click Add Book or Add Borrower to create new entries.

- Use the Borrow Records section to link books with borrowers.


## 🖼 Screenshots

### 📊 1. Dashboard
![Dashboard](https://github.com/smsnjr7/MidtermExam/blob/main/dashboard.png)
*Main dashboard view of the LibraTrack System.*

---

### 📚 2. Books Management
![Books Management](https://github.com/smsnjr7/MidtermExam/blob/main/books.png)
*Section for adding, editing, deleting, and viewing book records.*

---

### 🧍‍♂️ 3. Student Borrowers Page
![Borrowers](https://github.com/smsnjr7/MidtermExam/blob/main/Add_borrower.png)
*Interface for registering and managing borrower information.*

---

### 🔗 4. Borrowed Records
![Borrowed Records](https://github.com/smsnjr7/MidtermExam/blob/main/Students.png)
*Displays which books are currently borrowed and by whom.*

---

### 🔗 5. Add Books Page 
![Add Books ](https://github.com/smsnjr7/MidtermExam/blob/main/Add_book.png)
*Interface for adding books.*

---


## 👥 Contributors

- **Samson F. Alcantara Jr.**  
- **Casper Klein C. Valdez**

## 📝 License

This project is for educational purposes only and not intended for commercial use.
