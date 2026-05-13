# Trello Database Project

This project is a PostgreSQL database design inspired by the functionality of the Trello platform.

## Project Overview

The database was designed to simulate the core structure of a task management system similar to Trello. It includes relationships between users, boards, lists, tasks, comments, and responsibilities.

## Database Features

- User management
- Boards and lists structure
- Task creation and organization
- Task comments
- Many-to-many task responsibilities
- Relational database architecture
- Foreign key constraints
- PostgreSQL implementation

## Technologies Used

- PostgreSQL
- SQL
- pgAdmin

## Database Structure

Main relationships used in the project:

- Users → Boards : One-to-Many
- Boards → Lists : One-to-Many
- Lists → Tasks : One-to-Many
- Users ↔ Tasks : Many-to-Many
- Tasks → Comments : One-to-Many

## Files Included

- `trello.sql` — PostgreSQL database dump
- `scheme.png` — Database schema/architecture diagram

## Purpose

This project was created for practicing database design, SQL relationships, normalization, and backend data architecture concepts.
