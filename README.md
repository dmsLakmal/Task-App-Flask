# TaskApp

TaskApp is a simple task management application built with Flask and SQLAlchemy.

## Features

- Add new tasks
- View all tasks
- Delete tasks

## Requirements

- Python 3.x
- Flask
- Flask-SQLAlchemy

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/TaskApp.git
   cd TaskApp
2. Create a virtual environment:
   ```sh
   python -m venv TaskApp-env
3. Activate the virtual environment:
  On Windows:
  `TaskApp-env\Scripts\activate`
  On Unix or MacOS:
  `source TaskApp-env/bin/activate`

4. Install the required packages:
  `pip install -r requirements.txt`

5. Set up the database:
  ```sh
    python
    >>> from app import app, db
    >>> with app.app_context():
    ...     db.create_all()
    ...
```

# Running the Application
1. Start the Flask development server:
python app.py
2. Open your web browser and go to
   `http://127.0.0.1:5000/.`


## License
This project is licensed under the MIT License.


