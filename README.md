# Movie Management Application

---

## Overview

A desktop application developed in **C++ using the Qt framework** for managing a movie database.

The application supports multiple operating modes and storage mechanisms, demonstrating object-oriented design principles and layered architecture.

---

## Core Functionality

### Administrative Mode
- Add movies
- Remove movies
- Update movie information
- Display All Movies
- Undo action
- Redo action

### User Mode
- Browse available movies
- Open their trailers
- Save movies to a personal watchlist
- Like a movie
- Export watchlist (CSV / HTML)
- Open the watchlist

---

## Storage Strategies

The application supports two interchangeable repository implementations:

- **MemoryRepository** – in-memory storage
- **FileRepository** – persistent file-based storage (CSV/HTML)

This allows switching between temporary and persistent data handling without affecting the higher-level logic.

---

## Architecture

The project follows a layered design:

- **UI Layer** – Qt graphical interface
- **Service Layer** – business logic
- **Repository Layer** – data access

This separation ensures modularity and maintainability.

---

## Technologies

- C++
- Qt Framework
- STL Containers
- File I/O
- Object-Oriented Programming

---

## Design Principles Applied

- Encapsulation
- Abstraction
- Polymorphism
- Separation of Concerns
- Repository Pattern
- CRUD Operations

---

## How to Build and Run

1. Open the project in Qt Creator or Visual Studio (with Qt configured).
2. Build the project.
3. Run the application.
4. Select the desired mode at startup.

---

## Project Context

This project was developed as part of a university course on Object-Oriented Programming and software design.
