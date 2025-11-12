# AST---Based-Natural-Language-to-SQL-Translator

 

AST-Based Natural Language to SQL Translator
This project converts plain English text into SQL queries using Abstract Syntax Trees (ASTs).

Overview
The system uses NLP parsing and AST traversal to generate valid SQL statements from natural language input.

Example:

Input: "Show all students with marks above 80"
Output: SELECT * FROM students WHERE marks > 80;

Technologies Used
Python
NLTK, spaCy
AST module
SQLParse
Flask (for backend integration)
SQLite / PostgreSQL

Features
Converts text to SQL accurately using AST-based parsing
Handles basic SELECT, WHERE, and ORDER BY clauses
Extendable for multi-table joins and aggregations
Developed by Mansi Nikam (PCCOE, Pune)
