# Flask To-Do List Application

This is a simple to-do list web application built using Flask and SQLAlchemy. Users can add, edit, delete, complete, and reorder tasks.

## Features

- Add new tasks
- Edit existing tasks
- Mark tasks as complete or incomplete
- Delete tasks
- Reorder tasks using drag-and-drop

## Requirements

- Python 3.6+
- Flask
- Flask-SQLAlchemy
- Sortable.js (included in the HTML)

## Setup

1. Clone the repository:

```bash
git clone https://github.com/yourusername/flask-todo-app.git
cd flask-todo-app
```

2. Create a virtual environment and activate it:

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

3. Install the required packages:

```bash
pip install Flask Flask-SQLAlchemy
```

4. Run the application:

```bash
python app.py
```

5. Open your web browser and go to `http://127.0.0.1:8080`.

## File Structure

- `app.py`: The main Flask application file.
- `templates/index.html`: The HTML template for the to-do list.
- `static/`: Directory for static files (e.g., CSS, JavaScript).

## Database

The application uses SQLite for the database. The database file `todos.db` will be created automatically when you run the application.

## Updating Task Order

Tasks can be reordered using drag-and-drop functionality. The order is saved automatically when tasks are reordered.

## Routes

- `/`: The main page displaying the to-do list.
- `/add`: Route to add a new task (POST).
- `/update/<int:todo_id>`: Route to mark a task as complete/incomplete (GET).
- `/delete/<int:todo_id>`: Route to delete a task (GET).
- `/edit/<int:todo_id>`: Route to edit a task (POST).
- `/update_order`: Route to update the order of tasks (POST).

## Executable Release

We are excited to announce the release of the Flask To-Do List Application v1.0 as an executable file! This allows you to run the application without needing to install Python or any dependencies.

### Features:

- **Add Tasks**: Quickly add new tasks to your to-do list.
- **Edit Tasks**: Modify existing tasks to keep your list up-to-date.
- **Mark as Complete**: Easily mark tasks as complete or incomplete.
- **Delete Tasks**: Remove tasks that are no longer needed.
- **Reorder Tasks**: Organize your tasks by dragging and dropping them into your desired order.

### How to Use:

1. Download the executable file from the link below.
2. Run the executable file to start the application.
3. Open your web browser and go to `http://127.0.0.1:8080`.
4. Manage your tasks directly from the browser.

### System Requirements:

- Windows 7 or higher
- No need to install Python or any dependencies

**Download the executable:** [Link to the executable]

## Acknowledgements

This project uses the following libraries and frameworks:

- [Flask](https://flask.palletsprojects.com/)
- [Flask-SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/)
- [Sortable.js](https://sortablejs.github.io/Sortable/)

## License

This project is licensed under the MIT License.
