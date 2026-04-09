📚 Library Management System

A console-based Java application that automates library operations such as managing books, users, and transactions. This system helps reduce manual effort and efficiently track issued and returned books.

🎬 Demo
(https://drive.google.com/file/d/19z-nFOjAeXM8hJrsGEKHbzOvLZamyyxL/view?usp=drive_link)

🚀 Features
📖 Book Management
Add, update, and remove books
View all available books
👤 User Management
Register new users
🔄 Transaction Management
Issue books to users
Return books with due date tracking
💰 Fine Calculation
Automatic fine for late returns (₹10 per day after 7 days)
🔍 Search Functionality
Search books by title (can be extended to author)
🛠️ Technology Stack
Language: Java (Core Java, OOP)
Concepts Used:
Classes & Objects
Encapsulation
Collections (ArrayList)
Date & Time API
Interface: Console-based UI
📋 Prerequisites
Java JDK 8 or higher
Command Prompt / Terminal
(Optional) IDE like IntelliJ / Eclipse / VS Code
⚙️ Installation
Clone the repository:
git clone https://github.com/eswarallu/library-management-system.git
Navigate to project folder:
cd library-management-system
▶️ Running the Application

Compile all Java files:

javac model/*.java service/*.java main/*.java

Run the program:

java main.Main
📁 Project Structure
library-management-system/
│
├── model/
│   ├── Book.java
│   ├── User.java
│   └── Transaction.java
│
├── service/
│   └── LibraryService.java
│
├── main/
│   └── Main.java
