# To Do List React App

A simple To Do List application built with React. This app allows users to add tasks with a date, view the list of tasks, and delete tasks as needed.

## Features

- **Add Tasks:** Enter a task name and date to add it to your list.
- **Delete Tasks:** Remove tasks from your list with a single click.
- **No Task Message:** Displays a message when there are no tasks left.

## Components

- `AppName`: Displays the application name.
- `AddToDo`: Form for adding new tasks.
- `ToDoItems`: Shows the list of current tasks and allows deletion.
- `NoTask`: Shown when there are no tasks in the list.

## How It Works

- The app uses React's `useState` to manage the list of tasks.
- Adding a task appends it to the current list.
- Deleting a task removes it from the list by filtering out the selected task.
