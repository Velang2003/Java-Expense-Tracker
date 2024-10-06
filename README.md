# Expense Tracker

## Overview

Expense Tracker is a Java-based desktop application designed to help users manage their expenses efficiently. The application provides a user-friendly GUI that allows users to create accounts, log in, track individual expenses, and categorize them. It also supports adding and deleting categories and provides an overview of overall expenses.

## Features

- **Account Management**: Create and log in to user accounts.
- **Expense Tracking**: Add, view, and delete individual expenses.
- **Category Management**: Create new expense categories and avoid duplication.
- **Expense Overview**: View the total expenses and breakdown by category.

## Installation

**Clone the Repository**

   ```
   https://github.com/Velang2003/Expense-Tracker.git
   ```


# *BUILD OUTPUT DESCRIPTION*

When you build an Java application project that has a main class, the IDE
automatically copies all of the JAR
files on the projects classpath to your projects dist/lib folder. The IDE
also adds each of the JAR files to the Class-Path element in the application
JAR files manifest file (MANIFEST.MF).

## To run the project from the command line, go to the *dist* folder and
type the following:

```
java -jar ExpenceTracker/dist/Expence_Tracker.jar
```
To distribute this project, zip up the dist folder (including the lib folder)
and distribute the ZIP file.

## Notes:

* If two JAR files on the project classpath have the same name, only the first
JAR file is copied to the lib folder.
* Only JAR files are copied to the lib folder.
If the classpath contains other types of files or folders, these files (folders)
are not copied.
* If a library on the projects classpath also has a Class-Path element
specified in the manifest,the content of the Class-Path element has to be on
the projects runtime path.
* To set a main class in a standard Java project, right-click the project node
in the Projects window and choose Properties. Then click Run and enter the
class name in the Main Class field. Alternatively, you can manually type the
class name in the manifest Main-Class element.


## Usage

1. **Create an Account**: Open the application and follow the prompts to create a new account.
2. **Log In**: Use your credentials to log in to the application.
3. **Track Expenses**: Add expenses with details such as date, category, and amount.
4. **Manage Categories**: Add new categories as needed from the category management page.
5. **View Summary**: Check your overall expenses and category-wise breakdown.

## Contributing

Feel free to open issues or submit pull requests to enhance the project. Contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Java Development Kit (JDK 17)
- Java NetBeans
