# Android Inventory & Login App 
### Overview

This artifact is an enhanced version of my Android Inventory and Login Application originally created for CS 360 – Mobile Architecture and Programming. The project demonstrates my skills in mobile software engineering, secure application design, architectural refactoring, and database integration using modern Android component libraries.

The enhanced version incorporates significant improvements to code structure, security, maintainability, and usability.

### Artifact Structure
```
algorithms-avl-tree/
├── CS300_ProjectTwo.zip              # Original CS 300 submission
├── CS300_ProjectTwo_Enhanced.zip     # Enhanced AVL tree implementation for CS 499
└── README.md                         # Overview + enhancement summary
```


### Original Project Summary

The original Android app implemented basic functionality for:

User login using plain-text credential checks

Adding and viewing inventory items

Using activity-based logic with tight coupling

Temporary in-memory storage (no database)

While functional, the structure was not scalable and lacked modern Android architecture or secure authentication practices.

### For the capstone, I performed the following software engineering improvements:

###  1. Refactored to MVVM Architecture

Reorganized the entire application using Model–View–ViewModel (MVVM) to:

Separate UI from business logic

Improve maintainability

Improve testability

Align with Android best practices

### 2. Integrated Room Database

Added a persistent Room SQLite database:

Inventory items stored locally

DAO interfaces for safe database operations

Eliminates dependency on in-memory lists

Supports offline functionality

### 3. Implemented PBKDF2 Password Hashing

Replaced plain-text login checks with:

PBKDF2WithHmacSHA1 hashing

Salts for secure credential storage

OWASP-aligned password protection

Avoids security vulnerabilities common in mobile apps

### 4. Improved Code Quality and Organization

Added detailed comments and documentation

Standardized naming conventions

Improved lifecycle handling

Added ViewModels for inventory and authentication

### 5. Prepared JUnit testing structure

Created a foundation for ViewModel-level JUnit tests using:

Mock repositories

Decoupled business logic

### Skills Demonstrated

✔ Software engineering best practices

✔ Secure mobile authentication

✔ Android app architecture (MVVM)

✔ Local data persistence with Room

✔ Code refactoring & modularization

✔ Testable architecture design

✔ Use of modern Android Jetpack components


### How to Run the Enhanced Version

Download the ZIP from the enhanced folder

Extract into Android Studio

Let Gradle sync

Run on an emulator or physical device

Use the login screen to authenticate and access inventory management features

### Narrative Document
The detailed enhancement narrative for this artifact is included in the /narratives directory:
```
narratives/Artifact Narrative 1_Android Mobile App_LynneskaRivera.docx
```
