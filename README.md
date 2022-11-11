# Overview

This C++ program utilizes the sqlite3 library to perform CRUD operations. Users are presented with a simple command line interface, with which they can insert custom databases and tables, update existing values, view tables, and delete databases and tables.

To launch, start by making sure sqlite3 is installed and within your directory. Next, link it to the program by running "g++ main.cpp -l sqlite3 -o main", and compile by running "./main" in your terminal.

[Demo](https://youtu.be/y4Mnp4BIMrY)

# C++/sqlite3 Database

**Table Structure:**

ID---------INTEGER PRIMARY KEY AUTOINCREMENT </br>
NAME-------TEXT NOT NULL </br>
TITLE------TEXT NOT NULL </br>
NOTE-------NVARCHAR(500)  </br>

# Development Environment

**Software used:**
Language: C++
Libraries: sqlite3
IDE: VScode

# Useful Websites

{Make a list of websites that you found helpful in this project}
* [sqlite.org](https://sqlite.org/index.html)
* [tutorialspoint.com](https://www.tutorialspoint.com/sqlite)

# Future Work

* Add GUI
* Connect to MongoDB postgres server
* Add custom column insertion
