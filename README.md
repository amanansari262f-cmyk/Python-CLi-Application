# Python CLI Task Manager

A beginner-friendly command-line task manager built with Python. It lets you add, view, complete, and delete tasks. Tasks are saved locally in a JSON file.

## Features

- Add tasks with title validation
- View all tasks and their status
- Mark tasks as complete
- Delete tasks by ID
- Save tasks between sessions using JSON
- Handle invalid menu choices, invalid IDs, missing tasks, malformed JSON, and file errors
- Organized into modules (`main.py`, `task_manager/core.py`, `task_manager/storage.py`, and `task_manager/cli.py`)

## Requirements

- Python 3.9 or newer
- No third-party packages required

## Run the application

1. Download or clone this repository.
2. Open a terminal in the project folder.
3. Run:

   ```bash
   python main.py
   ```

   On some systems, use `python3 main.py`.

## Menu

1. View tasks
2. Add task
3. Mark task complete
4. Delete task
5. Exit

## Project structure

```text
python-cli-task-manager/
├── main.py
├── README.md
├── .gitignore
└── task_manager/
    ├── __init__.py
    ├── cli.py
    ├── core.py
    └── storage.py
```

`tasks.json` is created automatically after the first successful change and is excluded from Git so personal task data is not uploaded.

## Concepts demonstrated

- Functions and modules
- Lists and dictionaries
- Input validation
- Exceptions (`try` / `except`)
- JSON file handling
- A command-line menu loop

## Manual test checklist

- Add a task with a normal title.
- Try adding an empty title.
- View tasks.
- Mark an existing task complete.
- Enter a non-numeric ID.
- Enter an ID that does not exist.
- Delete a task.
- Exit and restart; confirm tasks remain saved.

## Author

Add your name here before publishing.
