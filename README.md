# 🍎 Fruit Store App

A simple console-based Fruit Store Management System developed using Python. This project demonstrates the use of Python modules, functions, dictionaries, file handling, logging, and menu-driven programming concepts.

## 📋 Features

### Fruit Manager

* Add new fruits to stock
* Store fruit quantity and price
* Save inventory data permanently using file handling

### Customer

* View available fruit stock
* Display fruit quantity and pricing information

### System Features

* Modular programming structure
* File handling using JSON
* Transaction storage support
* Log file generation
* Menu-driven interface
* Clean and simple console output

---

## 🛠 Technologies Used

* Python 3
* JSON
* File Handling
* Dictionaries
* Functions
* Modules
* Logging

---

## 📂 Project Structure

```text
Fruit_Store_App/
│
├── main.py
├── fruit_manager.py
├── customer.py
├── file_handler.py
├── logger.py
├── stock.txt
├── transactions.txt
└── store.log
```

---

## 🚀 How It Works

### Main Menu

```text
===== FRUIT STORE =====
1. Add Fruit
2. View Stock
3. Exit
```

### Add Fruit

The Fruit Manager can add a fruit by entering:

* Fruit Name
* Quantity
* Price

Example:

```text
Enter Fruit Name: Mango
Enter Quantity: 50
Enter Price: 100
```

### View Stock

Displays all available fruits:

```text
Mango | Qty=50 | Price=100.0
Apple | Qty=25 | Price=120.0
```

---

## 💾 Data Storage

### stock.txt

Stores fruit inventory in JSON format.

Example:

```json
{
    "Mango": {
        "quantity": 50,
        "price": 100
    }
}
```

### store.log

Stores application activity logs with timestamps.

Example:

```text
2026-06-10 15:30:20.123456 - Added Mango
```

---

## ▶️ Running the Application

Clone the repository:

```bash
git clone https://github.com/your-username/Fruit_Store_App.git
```

Navigate to the project folder:

```bash
cd Fruit_Store_App
```

Run the application:

```bash
python main.py
```

---

## 📚 Concepts Demonstrated

* Python Functions
* Modular Programming
* Dictionaries
* File Handling
* JSON Operations
* Logging
* Menu-Driven Applications
* Basic Inventory Management

---

## 🎯 Learning Objectives

This project was created to practice:

* Python project structuring
* Creating reusable modules
* Reading and writing files
* Maintaining application logs
* Building interactive console applications

---

## 👨‍💻 Author

**Ayush Parashar**

Python Fruit Store Management System Project
