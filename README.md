# Task manager

A simple and elegant To-Do List app built with **SwiftUI**. This app allows you to manage your tasks, mark them as completed, and view task details. It also supports **dark mode** and smooth animations for a great user experience.

---

## Features

- **Add Tasks**: Easily add new tasks with a title and details.
- **Mark Tasks as Completed**: Toggle the completion status of tasks with a checkmark button.
- **Task Details**: Navigate to a detailed view of each task.
- **Delete Tasks**: Swipe to delete tasks from the list.
- **Dark Mode**: Toggle between light and dark mode for better visibility.
- **Smooth Animations**: Enjoy smooth animations when adding, deleting, or toggling tasks.

## Code Structure
The project is organized into the following files and folders:


TaskModel.swift: Defines the Task data model.


TaskViewModel.swift: Manages the state and logic for tasks.


ContentView.swift: The main view displaying the task list.


AddTaskView.swift: A view for adding new tasks.


TaskRowView.swift: A view for displaying individual tasks in the list.


TaskDetailView.swift: A view for displaying task details.

## How to Use
Add a Task:

Tap the "Add Task" button at the top of the screen.

Enter a title and details for the task.

Tap the "+" button to add the task to the list.

Mark a Task as Completed:

Tap the checkmark button next to a task to toggle its completion status.

View Task Details:

Tap on a task's title or description to navigate to its details page.

Delete a Task:

Swipe left on a task in the list and tap Delete.

Toggle Dark Mode:

Use the Dark Mode toggle at the bottom of the screen to switch between light and dark themes.

## Technologies Used
SwiftUI: For building the user interface.

ObservableObject: For state management.

NavigationStack: For navigation between screens.

Animations: For smooth transitions when adding, deleting, or toggling tasks.

