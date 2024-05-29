# To-Do List Web Application

A simple, dark-themed To-Do List web application built with Python and Flask. This application allows users to add, edit, complete, and delete tasks. The tasks are stored in an SQLite database.

## Features

- Dark mode user interface
- Add new tasks
- Edit existing tasks
- Mark tasks as complete or incomplete
- Delete tasks
- Animated buttons and a visually appealing list

## Prerequisites

- Python 3.x
- Flask
- Flask-SQLAlchemy

## Getting Started

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/wizard-boy-yt/TO-DO-LIST-app.git
    cd TODO-List-FlaskApp
    ```

2. Create a virtual environment and activate it:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install Flask Flask-SQLAlchemy
    ```

### Running the Application

1. Ensure you are in the project directory and the virtual environment is activated.

2. Run the application:
    ```bash
    python app.py
    ```

3. Open your web browser and navigate to:
    ```
    http://127.0.0.1:8080
    ```

## Project Structure

```
todo-list-flask-app/
│
├── app.py
├── templates/
│   └── index.html
├── venv/
│   └── ... (virtual environment files)
├── README.md
└── requirements.txt
```

- `app.py`: The main Flask application file containing route definitions and database models.
- `templates/index.html`: The HTML template for rendering the To-Do List.
- `venv/`: The virtual environment directory.
- `README.md`: This README file.
- `requirements.txt`: File for specifying the Python dependencies.

## Routes

- `/`: Displays the to-do list.
- `/add`: Adds a new to-do item.
- `/update/<int:todo_id>`: Toggles the completion status of a to-do item.
- `/delete/<int:todo_id>`: Deletes a to-do item.
- `/edit/<int:todo_id>`: Edits an existing to-do item.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Flask](https://flask.palletsprojects.com/)
- [Flask-SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## Contact

- GitHub: [Soumyadeep](https://github.com/wizard-boy-yt)
