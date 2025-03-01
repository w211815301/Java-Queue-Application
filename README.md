# Java Queue Application

## Overview
This is a Java console application that implements an in-memory queue to manage "Task" objects. The application allows the user to:
- Add a Task
- List all Tasks in the queue
- Remove a Task from the front of the queue
- Exit the application

## Objectives
- **Implement a Queue:** Utilize Java’s built-in data structures (e.g., `LinkedList` or `ArrayDeque`) to implement a queue.
- **Command-Line Interaction:** Build a simple menu-driven console application.
- **Version Control:** Gain experience with Git and GitHub, including committing, branching, and pushing code.
- **Documentation:** Create a `README.md` file that explains how to run the application.

---

## Project Structure

java-queue-application/ │ README.md │ .gitignore └───src/ │ QueueApp.java └───model/ │ Task.java └───service/ TaskQueueService.java




- **model/Task.java:** Contains the `Task` class with `id` and `description` fields.
- **service/TaskQueueService.java:** Manages the in-memory queue using `LinkedList<Task>`.
- **QueueApp.java:** Main application code with a command-line interface.

---

## Features
1. **Add a Task** – Enqueue a new task by entering an ID and description.
2. **List Tasks** – Display all tasks currently in the queue.
3. **Remove a Task** – Dequeue (retrieve and remove) the first task from the queue.
4. **Exit the Application** – Close the console application.

---

## Requirements
- Java Development Kit (JDK 8 or higher)
- Any IDE (e.g., IntelliJ IDEA, Eclipse) or a command-line interface

---

## How to Compile and Run

### Compile:
Open a terminal and navigate to the root directory of your project, then run:
```bash
javac -d bin src/model/Task.java src/service/TaskQueueService.java src/QueueApp.java
