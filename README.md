# Inventory Management System

#### Video Demo: https://youtube.com/PASTE-YOUR-UNLISTED-VIDEO-LINK-HERE

#### Description:

The Inventory Management System is a Python-based application created as a final project for Unit 7. The goal of this project is to demonstrate the ability to design and implement a complete Python program that applies core programming concepts such as control structures, object-oriented programming, file handling, error handling, and the use of external libraries.

This application simulates a simple inventory system that could be used by a small business. The program allows users to add new products, view existing inventory, update product quantities, remove products, and export inventory reports. All inventory data is stored in a file so that information is preserved even after the program is closed and restarted. This makes the project more advanced than basic lab assignments that only run temporarily in memory.

The project is written entirely in Python and follows a modular design. The program includes a Product class, which represents individual inventory items and groups related data such as name, price, and quantity into a single object. This object-oriented approach improves organization, readability, and maintainability of the code. Using a class also makes it easier to expand the system in the future, such as adding categories, suppliers, or product IDs.

Control structures are used throughout the application. A while loop is used to keep the program running until the user chooses to exit. Conditional statements control the menu system and determine which action the program performs based on user input. For loops are used to iterate through inventory data when displaying products or searching for a specific item.

Error handling is an important part of this project. The program uses try and except blocks to prevent crashes caused by invalid input, file errors, or corrupted data. For example, if a user enters text instead of a number for price or quantity, the program safely prompts the user to try again. If the inventory file does not exist or cannot be read, the program starts with an empty inventory instead of failing.

File handling is implemented using Python’s built-in json module. Inventory data is saved to a JSON file, which allows the data to persist across multiple runs of the program. JSON was chosen because it is structured, human-readable, and commonly used in real-world applications. The program also includes an option to export an inventory report to a timestamped text file, demonstrating additional file output functionality.

The project consists of the following files:

- TermProject.py: The main Python file containing the Product class, main function, and all supporting functions for inventory management.
- README.md: Project documentation explaining the purpose, design decisions, and structure of the application.
- requirements.txt: A file listing required libraries. This project uses only Python standard libraries, so no external packages are required.

Several key design decisions were made during development. A menu-driven interface was chosen to keep the program simple and user-friendly. Input validation functions were created to avoid repeating error-handling logic. JSON storage was selected over plain text files to better represent structured data.

Overall, this project demonstrates the ability to apply Python programming concepts in a practical and realistic way. It meets all course objectives by using Python syntax, control structures, object-oriented programming, error handling, file handling, and standard libraries. The Inventory Management System reflects real-world software design practices and provides a strong foundation for future enhancements.
