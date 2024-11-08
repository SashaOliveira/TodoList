React Todo List App 📝
A simple, elegant Todo List application built with React and Material-UI. This app saves your todos locally so you can keep track of your tasks even after refreshing the page.

-Table of Contents
Features
Installation
Usage
Components
Screenshots
License

-Features
Add, Toggle, and Delete Todos: Keep track of tasks, mark them complete, or remove them from the list.
Local Storage: All todos are saved locally, so your tasks will persist even after a page refresh.
Responsive Design: Optimized for various screen sizes.
Material-UI Design: Uses Material-UI components for a clean and intuitive UI.

-Usage
Add a Task: Enter your task in the text field and click the submit icon or press Enter to add it to the list.
Mark as Complete: Click on a task to toggle its completion status.
Delete a Task: Click the delete icon next to a task to remove it.
Components
App.js
The main component that renders the navigation bar and the TodoList component.

-TodoList.js
Contains the todo list and manages the app's state. It fetches data from local storage when the app loads and saves updates to local storage whenever the todos list changes.

getInitialData function: Fetches saved todos from local storage.
useEffect hook: Watches for changes in the todos state and saves it to local storage.
Navbar.js
Displays the app's title using Material-UI's AppBar and Toolbar.

-TodoForm.js
Handles adding new todos. It uses Material-UI's TextField and a submit button icon for adding tasks to the list.

-TodoItem.js
Displays each todo with its text, completion status, and options to toggle or delete the task.
