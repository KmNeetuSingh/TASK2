# To-Do App

## Description
This repository contains a web-based To-Do App created as part of the Alpha internship. The To-Do App allows users to add, delete, and mark tasks as completed, providing a simple and effective task management solution.

## Features
- **React:** Utilizes React for building the user interface with components and state management.
- **HTML:** Structuring the web page for the To-Do App.
- **CSS:** Styling the web page to enhance user experience with a clean and modern design.

## Technologies Used
- HTML
- CSS
- JavaScript (React)

## How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/todo-app.git
    ```
2. Navigate to the project directory:
    ```bash
    cd todo-app
    ```
3. Open `index.html` in a web browser to view the To-Do App.

## Code Explanation
- **HTML**: The HTML structure includes a root div where the React app is rendered.
- **CSS**: The CSS styles the application, providing a visually appealing interface.
- **JavaScript**: The JavaScript, written in React, handles the state management and UI updates for the To-Do App.

## Detailed Code Description
The To-Do App consists of several key components and functions:

1. **TodoItem Component**: Represents an individual to-do item, including a checkbox for completion and a delete button.
2. **TodoList Component**: Renders a list of TodoItem components, managing the list of tasks.
3. **AddTodo Component**: Provides an input field and button for adding new tasks.
4. **TodoApp Component**: The main app component that holds the state for the list of tasks and passes down necessary props and functions to child components.

### TodoItem Component
Handles rendering of individual to-do items with their respective delete and completion toggle functions.

### TodoList Component
Maps over the list of to-dos and renders a TodoItem for each, passing necessary props for deletion and completion toggling.

### AddTodo Component
Manages the input state for new to-dos and handles adding them to the list.

### TodoApp Component
Contains the state for the entire app, managing the list of to-dos and providing functions for adding, deleting, and toggling completion of tasks
