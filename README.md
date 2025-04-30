# Hotel Management System (HMS)

## 📌 Overview

The Hotel Management System (HMS) is a Java-based desktop application that allows hotel staff to manage customer information, room bookings, and other administrative tasks. It uses Java Swing for the graphical user interface (GUI) and includes basic database interaction functionality.

## 🚀 Features

- Add, update, and view customer details
- Hotel booking interface via GUI
- Database connection for persistent data storage
- Modular and maintainable Java code
- Simple and intuitive user interface

## 🗂️ Project Structure

```
hms/
├── Customer.java               # Defines the customer model
├── CustomerDataStore.java     # Handles storing and retrieving customer data
├── CustomerManagementGUI.java # GUI for managing customer-related tasks
├── HotelManagementGUI.java    # Main GUI for hotel management interface
├── DatabaseConnection.java    # Manages database connectivity
├── Main.java                  # Entry point of the application
├── *.class                    # Precompiled Java class files
└── resources/                 # (Optional) Resources like icons/images
```

## 🔧 Requirements

- Java JDK 8 or later
- (Optional) MySQL Database (or modify for any other supported DB)

## 🛠️ Setup Instructions

1. **Clone or download** this repository and unzip it.
2. **Navigate** to the project folder containing the `.java` files.
3. **Compile** the Java source code:
   ```bash
   javac hms/*.java
   ```
4. **Run** the application:
   ```bash
   java hms.Main
   ```

## ⚙️ Configuration

If your application connects to a database, configure the credentials and URL in `DatabaseConnection.java`:

```java
String url = "jdbc:mysql://localhost:3306/hotel_db";
String username = "your_username";
String password = "your_password";
```

Ensure that your MySQL server is running and that the database `hotel_db` exists with the required tables.

## 🧩 Modules Description

| Module/Class Name            | Purpose                                      |
|-----------------------------|----------------------------------------------|
| `Customer.java`             | Encapsulates customer attributes             |
| `CustomerDataStore.java`    | Provides methods to store/retrieve data      |
| `CustomerManagementGUI.java`| GUI to manage customer actions               |
| `HotelManagementGUI.java`   | Main window for hotel management features    |
| `DatabaseConnection.java`   | Database utility for connecting via JDBC     |
| `Main.java`                 | Launches the HMS system                      |

## 👨‍💻 Author

**Bonu Sai Ganesh**  
B.Tech, Computer Science and Engineering  
SRM-AP University

## 📃 License

This project is intended for academic and educational purposes. Feel free to modify and reuse the code as needed for learning and development.
