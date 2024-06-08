# BBL Expense Tracker

BBL Expense Tracker is a web application built with Django, Python, SQLite, HTML, CSS, and Bootstrap. It allows users to track and manage their expenses efficiently. This project is developed as a portfolio project for ALX.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## Features
- User authentication (registration, login, logout)
- Add, edit, and delete expenses
- View a list of all expenses
- Filter expenses by date, category, etc.
- Responsive design with Bootstrap

## Technologies Used
- *Backend*: Django, Python
- *Database*: SQLite
- *Frontend*: HTML, CSS, Bootstrap
- *Others*: SMTP for email notifications

## Installation

### Prerequisites
- Python 3.x
- Django
- Git

### Steps
1. *Clone the repository*:
    bash
    git clone https://github.com/ElizabethAgada/BBL_Expense_tracker.git
    
2. *Navigate to the project directory*:
    bash
    cd BBL-Expense-tracker
    
3. *Create and activate a virtual environment*:
    bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    
4. *Install the required packages*:
    bash
    pip install -r requirements.txt
    
5. **Configure the database settings in expense_tracker/settings.py**:
    The default configuration uses SQLite:
    python
    DATABASES = {
        'default': {
            'ENGINE': 'django.db.backends.sqlite3',
            'NAME': os.path.join(BASE_DIR, 'db.sqlite3'),
        }
    }
    
6. *Apply migrations*:
    bash
    python manage.py makemigrations
    python manage.py migrate
    
7. *Create a superuser to access the admin panel*:
    bash
    python manage.py createsuperuser
    
8. *Run the development server*:
    bash
    python manage.py runserver
    

## Usage
- Open a web browser and go to http://127.0.0.1:8000/
- Register a new user or login with an existing account
- Start adding, editing, and managing your expenses

## Screenshots
Include some screenshots of the application here.

## Contributing
Contributions are welcome! Please create an issue or submit a pull request for any enhancements or bug fixes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.