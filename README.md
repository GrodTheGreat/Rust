# Rust Practice
This repo is a place to store some projects as I practice Rust

## Projects
### Project 1: Hello, World!
**Overview:** The classic first program in any language.
**Skills Focus:** Basic syntax, setting up a Rust development environment, compiling, and running a program.
**Description:** Write a simple program that prints "Hello, World!" to the console.
**Technologies/Frameworks:** Rust standard library.

### Project 2: Guessing Game
**Overview:** A simple command-line guessing game.
**Skills Focus:** Basic input/output, control flow (if/else, loops), error handling, random number generation.
**Description:** Create a game where the computer randomly selects a number, and the player has to guess it. The program should provide feedback if the guess is too high, too low, or correct.
**Technologies/Frameworks:** Rust standard library.

### Project 3: Basic Calculator
**Overview:** A command-line calculator that can perform basic arithmetic operations.
**Skills Focus:** Functions, error handling, parsing user input.
**Description:** Implement a calculator that takes user input in the form of "2 + 2" and prints the result. It should support addition, subtraction, multiplication, and division.
**Technologies/Frameworks:** Rust standard library.

### Project 4: Simple To-Do List
**Overview:** A basic command-line to-do list application.
**Skills Focus:** Data structures (e.g., vectors, structs), file I/O, basic persistence.
**Description:** Create a to-do list where users can add, remove, and view tasks. Store the tasks in a file so that they persist between runs.
**Technologies/Frameworks:** Rust standard library.

### Project 5: Web Scraper
**Overview:** A tool to scrape data from a website.
**Skills Focus:** HTTP requests, error handling, external crates.
**Description:** Write a program that fetches and parses data from a website. For example, scrape headlines from a news website.
**Technologies/Frameworks:** `reqwest` for HTTP requests, `scraper` for parsing HTML.

### Project 6: REST API Client
**Overview:** A client for interacting with a RESTful web service.
**Skills Focus:** HTTP requests, JSON parsing, error handling, external crates.
**Description:** Create a client that interacts with a public REST API (e.g., a weather service API). The client should fetch data and display it in a user-friendly format.
**Technologies/Frameworks:** `reqwest` for HTTP requests, `serde` for JSON parsing.

### Project 7: Basic Web Server
**Overview:** A simple web server that serves static files.
**Skills Focus:** Networking, HTTP, concurrency.
**Description:** Implement a basic web server that can serve static files (e.g., HTML, CSS, JS). Handle basic HTTP methods (GET, POST).
**Technologies/Frameworks:** `hyper` or `actix-web`.

### Project 8: Chat Application
**Overview:** A real-time chat application.
**Skills Focus:** Networking, concurrency, WebSockets.
**Description:** Create a command-line chat application where multiple users can send and receive messages in real-time.
**Technologies/Frameworks:** `tokio` for asynchronous programming, `tungstenite` for WebSockets.

### Project 9: Database Integration
**Overview:** A CRUD application with database integration.
**Skills Focus:** Database interaction, SQL, data persistence.
**Description:** Build a command-line application to manage a collection of items (e.g., a book collection). Implement create, read, update, and delete (CRUD) operations with a SQLite database.
**Technologies/Frameworks:** `rusqlite` for SQLite database integration.

### Project 10: Web Application
**Overview:** A full-stack web application.
**Skills Focus:** Web development, frontend-backend interaction, database integration.
**Description:** Develop a web application with a frontend (HTML/CSS/JS) and a Rust backend. Implement user authentication, CRUD operations, and data persistence.
**Technologies/Frameworks:** `actix-web` or `rocket` for the backend, `diesel` for database integration, and basic HTML/CSS/JS for the frontend.

### Summary of Skills to Focus On:
1. **Basic Syntax and Concepts:** Variables, data types, functions, control flow.
2. **Error Handling:** Result and Option types, error propagation.
3. **Data Structures:** Vectors, HashMaps, structs, enums.
4. **Concurrency:** Async programming, threads, channels.
5. **Networking:** HTTP, WebSockets, asynchronous I/O.
6. **File I/O:** Reading from and writing to files.
7. **External Crates:** Using and managing external libraries.
8. **Web Development:** HTTP servers, routing, frontend-backend interaction.
9. **Database Integration:** SQL, ORM (Object-Relational Mapping).
