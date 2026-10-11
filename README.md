# Contact Management App

## Project Description
This is a Java-based Contact Management Application. It helps users store and manage contact details.

## Features
- Add new contacts
- View all contacts
- Search contacts by name or phone number
- Edit existing contacts
- Delete contacts
- Validate email addresses and mobile numbers
- Save contacts in a CSV file so they remain available after restarting the application

## Technologies Used
- Java
- Java Collections
- File Handling
- CSV Storage

## Requirements
- JDK 17 or later
- Visual Studio Code or another Java editor

## How to Run

Open the terminal in the project folder and execute:

```bash
javac -d out src/Contact.java src/ContactService.java src/Main.java
java -cp out Main
```

## Project Structure
- `src/Contact.java` – Stores contact details
- `src/ContactService.java` – Handles contact operations and file storage
- `src/Main.java` – Displays the menu and accepts user input
- `contacts.csv` – Stores saved contacts

## Author
Student Java Programming Internship Project