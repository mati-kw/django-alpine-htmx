# Django Alpine HTMX Project

This is a Django project configured to use Alpine.js and HTMX. Follow the steps below to clone the repository, set up the virtual environment, install dependencies, and run the application.

## Prerequisites

- Python 3.8 or higher
- pip
- pipenv
- Git

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/mati-kw/django-alpine-htmx.git
cd django-alpine-htmx
```

2. Set Up the Virtual Environment
Make sure you have pipenv installed. If not, you can install it using pip:


``` bash
pip install pipenv
```
3. Install Dependencies
Use pipenv to install all required dependencies:

```bash
pipenv install
```

4. Activate the Virtual Environment
Activate the virtual environment created by pipenv:

```bash
pipenv shell
```
5. Set Up the Database
Apply the migrations to set up the database:

```bash
python manage.py migrate
```

6. Create a Superuser
Create a superuser to access the Django admin:

```bash
python manage.py createsuperuser
```
7. Run the Development Server
Start the development server:

```bash
python manage.py runserver
```
Open your browser and navigate to http://127.0.0.1:8000/ to see the application in action.

Static Files
Static files (HTMX and Alpine.js) are included in the main/static/js/ directory and are loaded in the base template.

Project Structure
config/: Contains the Django project settings.
main/: Contains the main application, including views, templates, and static files.
templates/: Directory for HTML templates.
static/: Directory for static files like JavaScript and CSS.
Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request.

License
This project is licensed under the MIT License.
