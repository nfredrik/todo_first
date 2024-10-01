# Flask To-Do List App

This is a simple **To-Do List** web application built using Python's Flask framework. It allows users to add and delete tasks. The tasks are stored in an in-memory list (i.e., not persisted in a database). The app renders a basic HTML page for task management and provides API routes for adding and deleting tasks.

## Features
- **Add a Task**: Users can add new tasks to the list via a form.
- **Delete a Task**: Tasks can be deleted via a DELETE request.
- **In-memory Storage**: Tasks are stored in a Python list and will be cleared when the server restarts.

## Project Structure

- `app.py`: Main application file containing the Flask routes and logic.
- `templates/index.html`: HTML template to render the tasks and the form for adding new tasks.

## Routes

### 1. Index Page (View Tasks)
- **URL**: `/`
- **Method**: `GET`
- **Description**: Renders the main page displaying all tasks.

#### Example:
```html
GET http://localhost:5000/
