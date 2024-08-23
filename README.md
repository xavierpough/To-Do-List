# To-Do List Application

## Overview

This project is a simple yet functional To-Do list application designed to help users manage their tasks efficiently. The application is built using Vue.js and styled with Bootstrap, incorporating Font Awesome icons. The project follows the given guidelines to create a responsive and user-friendly interface that works across mobile and desktop screens.

## Features

### User Interface
* Task List Display: View all tasks in a clean and organized list.
* Add New Tasks: Create a new task using a text input.
* Complete Tasks: Mark tasks as complete, with a visual distinction between completed and uncompleted tasks.
* Delete Tasks: Remove tasks from the list.
* Responsive Design: The interface adapts to both mobile and desktop screens for a seamless experience.

### Functionality
* Create Task: Users can create tasks with a simple text input. Tasks cannot be created without a title.
* Complete Task: Users can mark tasks as complete, which will visually distinguish them from incomplete tasks.
* Delete Task: Users can delete tasks, with an optional confirmation prompt for safety.
* Show/Hide Completed Tasks: Users have the option to toggle the visibility of completed tasks.

### Storage
* Persistent Storage: Tasks are stored in the browser’s localStorage, ensuring that the task list persists between page reloads.

### Error Handling
* Validation: Tasks cannot be created without a title, preventing empty tasks from being added to the list.

### Bonus Features
* Delete Confirmation: Before a task is deleted, the user is prompted with a confirmation message.
* Edit Task Title: Users can edit the title of an existing task.


### Installation and Setup
To run the application locally:

1. Clone the Repository:
  > git clone https://github.com/xavierpough/todo-list-app.git
2. Navigate to the Project Directory:
  > cd todo-list-app
3. Install Dependencies:
  > npm install
4. Run the Application:
  > npm run serve
