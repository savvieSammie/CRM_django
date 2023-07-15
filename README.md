# Django CRM

Django CRM is a customer relationship management system built using Django framework. It provides a platform to manage customer interactions, track leads, and organize sales and customer support activities.

## Features

- User authentication: Register, login, and manage user accounts with role-based access control.
- Customer management: Create, view, update, and delete customer profiles.
- Lead management: Track leads, assign owners, and update lead status.
- Sales pipeline: Monitor and manage sales opportunities through various stages.
- Task management: Create tasks, assign them to users, and track their progress.
- Communication history: Log customer interactions, calls, emails, and notes.
- Reporting and analytics: Generate reports and gain insights into sales performance.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/savvieSammie/CRM_django.git
   ```

## Navigate to the project directory:

```bash
cd django-crm
```

## Create a virtual environment and activate it:

for mac:

```bash
python3 -m venv env
source env/bin/activate  # For Linux/Mac
```

for windows:

```bash
env\Scripts\activate  # For Windows
```


### Apply database migrations:

```bash
python manage.py migrate
```

### Start the development server:

```bash
python manage.py runserver
```

## Access the application in your web browser at http://localhost:8000.

## Configuration

Django settings: Customize your application's settings in the settings.py file.
Database: Configure the database settings in the DATABASES section of settings.py.
Static files: Place static files (CSS, JavaScript, etc.) in the static directory.
Templates: Modify and create HTML templates in the templates directory.


## Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make the necessary changes and commit them.
- Push your changes to your forked repository.
- Submit a pull request to the main repository.


### License
This project is licensed under the MIT License.

