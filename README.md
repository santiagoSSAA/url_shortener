# URL Shortener - Django Rest Framework

![Project Logo](url-shortener-logo.png) <!-- Replace with your project logo or relevant image -->

Create short, unique URLs for long URLs with this URL shortening service built using Django Rest Framework (DRF). Validate URLs, store mappings in a database, and handle redirects with ease.

## Features

- Generate short, unique URLs for long URLs entered by users
- Robust URL validation to ensure data integrity
- Store URL mappings securely in a PostgreSQL database
- Seamlessly redirect users from short URLs to the original ones
- Powered by Django Rest Framework for efficient and scalable RESTful API development

## Tech Stack

- Django: A high-level Python web framework for rapid development
- Django Rest Framework: A powerful toolkit for building Web APIs in Django
- PostgreSQL: A reliable relational database management system for data storage
- Gunicorn: A Python WSGI HTTP Server for seamless production deployment
- Heroku: A cloud platform for hosting the deployed application with ease

## Getting Started

1. Clone the repository: `git clone https://github.com/your-username/url-shortener-drf.git`
2. Install project dependencies: `pip install -r requirements.txt`
3. Configure your database settings (e.g., PostgreSQL) in the `settings.py` file.
4. Apply migrations to set up the database: `python manage.py migrate`
5. Start the development server: `python manage.py runserver`

## Contributing

We welcome contributions to improve the project! To contribute:

1. Fork the repository, create a new branch, and make your enhancements.
2. Submit a pull request describing the changes you've made.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Further Information

For detailed documentation and additional information, please refer to the project's [Wiki](https://github.com/your-username/url-shortener-drf/wiki).

Let's shorten those URLs together and simplify the way we share links! ✂️🔗
