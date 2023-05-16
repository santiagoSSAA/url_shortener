URL Shortener - Django Rest Framework

This is a URL shortening service built using Django Rest Framework (DRF). It allows users to enter long URLs and generates short, unique URLs that redirect to the original ones. The project implements features like URL validation, storage of mappings in a database, and handling redirects.

Features:
- Create short, unique URLs for long URLs
- Validate URLs entered by users
- Store URL mappings in a database
- Redirect users from short URLs to the original ones
- Built with Django Rest Framework for RESTful API development

Tech Stack:
- Django: Python web framework for building the backend
- Django Rest Framework: A powerful toolkit for building Web APIs
- PostgreSQL: Relational database management system for data storage
- Gunicorn: Python WSGI HTTP Server for production deployment
- Heroku: Cloud platform used for hosting the deployed application

Getting Started:
1. Clone the repository: `git clone https://github.com/your-username/url-shortener-drf.git`
2. Install the project dependencies: `pip install -r requirements.txt`
3. Set up your database (e.g., PostgreSQL) and update the database configuration in settings.py.
4. Apply migrations: `python manage.py migrate`
5. Run the development server: `python manage.py runserver`

Contributing:
- Fork the repository, create a new branch, and make your contributions.
- Submit a pull request detailing the changes you've made.

License:
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
