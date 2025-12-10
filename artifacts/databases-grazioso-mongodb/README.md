# Grazioso Salvare MongoDB Artifact
Overview

This artifact was originally created for CS 340 – Client/Server Development and expanded for CS 499 to demonstrate advanced database design, CRUD logic, authentication, and professional data workflow management.

The project uses:

MongoDB

Python

PyMongo

Jupyter Notebook

It manages a dataset of rescue animals for Grazioso Salvare and supports full Create, Read, Update, and Delete operations.
Original Project Summary

### Artifact Structure

databases-grazioso-mongodb/
├── original/ # Original CS 340 CRUD module + Jupyter notebook
├── enhanced/ # Enhanced CRUD logic, authentication steps, and notebook workflow
└── README.md # Overview + enhancement summary

### In the original version, the application:

Loaded CSV animal data

Connected to MongoDB

Provided basic CRUD operations

Demonstrated notebook-based data exploration

While functional, it needed:

Stronger error handling

Better query design

Authentication setup for MongoDB

### Improved structure for analysis
Enhancements for CS 499

1. Improved CRUD Module

I strengthened the CRUD class by:

Adding better exception handling

Implementing safe update and delete logic

Adding validation before DB operations

Standardizing return structures for consistency


2. MongoDB Authentication Setup

I configured a secure MongoDB user and updated the connection string accordingly:

Username/password authentication

Permissions limited to the relevant database

Secure connection flow aligned with MongoDB best practices


3. Updated Jupyter Notebook Workflow

I reorganized the notebook to:

Separate CRUD testing vs. data analysis

Add placeholder visualization cells (charts, filters, etc.)

Improve Markdown explanation and usability

The notebook is now significantly more readable and ready for analysis/expansion.

### How to Run

Install MongoDB locally OR connect to a remote MongoDB Atlas instance

Install dependencies:

pip install pymongo pandas


Open the Jupyter Notebook

Update the connection string with your credentials

Run the CRUD testing cells
