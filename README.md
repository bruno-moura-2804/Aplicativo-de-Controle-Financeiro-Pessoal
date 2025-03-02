
This project is a Personal Finance Management Application developed in Java, designed to provide a simple and efficient tool for managing personal finances. The application allows users to record and track their income and expenses, calculate the current balance, and generate detailed reports of transactions, making it easier to control and plan finances.

Key Features:
Add Transactions: Users can add both income (incoming money) and expenses (outgoing money), including the amount, description, and date of the transaction. The transaction type is determined by the user when entering the data.

Automatic Balance Calculation: The application automatically calculates the current balance by adding all income and subtracting all expenses. This feature provides a clear view of the user's financial health in real-time.

Generate Reports: The system generates reports with all recorded transactions, displaying detailed information such as date, transaction type, description, and amount. These reports are shown directly in the console.

Simple Command Line Interface (CLI): User interaction is performed via the terminal (command line), where they can access the application's functionalities through a menu of options.

Technologies Used:

Java: The primary language used for developing the application, utilizing Object-Oriented Programming (OOP) concepts to organize and structure the code.
Git: A version control system used to manage the source code and facilitate collaborative work.
Project Structure:
Transaction Class: Represents a financial transaction, storing details such as amount, type (income or expense), description, and transaction date.

FinanceManager Class: Responsible for managing financial transactions, including adding new transactions, calculating the balance, and generating reports.

Main Class: The main class that interacts with the user via a console menu. It allows the user to add transactions, check the balance, and view reports.

Potential Improvements:
Data Persistence: Implement functionality to save transactions in a database or file (e.g., JSON or SQLite), so that data is not lost when the application is closed.

Graphical User Interface (GUI): Develop a graphical user interface using JavaFX or Swing to provide a more interactive and visual user experience.

Financial Analysis: Add features like expense-by-category charts, monthly reports, budget projections, and other tools to aid financial control.

User Authentication: Implement a user authentication system, allowing multiple users to use the same application with separate data.

How to Run the Project:
Clone this repository to your local machine.
Compile and run the code using IntelliJ IDEA or any other IDE that supports Java.
Interact with the application directly through the terminal, using the menu options.
