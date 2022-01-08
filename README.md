# TinyApp Project

[TinyApp](https://tinyapp-pochiman.herokuapp.com/) is a full stack web application built with Python and Django that allows users to shorten long URLs (à la bit.ly).

## Final Product

!["login"](https://github.com/pochiman/TinyApp/blob/master/docs/login.png)
!["main"](https://github.com/pochiman/TinyApp/blob/master/docs/main.png)
!["dashboard"](https://github.com/pochiman/TinyApp/blob/master/docs/dashboard.png)

## Getting Started

1. Clone this repository onto your local device.
2. Set up a virtual environment.
3. Install dependencies using the `pip install requirements.txt` command.
4. Set up a postgres or sqlite database.  If a postgres database is being used, make sure to populate the secrets in a .env file.
5. Run the migrations using the `python manage.py migrate` command.
6. Run the development web server using the `python manage.py runserver` command.
7. The app will be served at <http://127.0.0.1:8000/> which should be accessible from your browser.
8. Create a superuser using the `python manage.py createsuperuser`command to access the <http://127.0.0.1:8000/admin/> page.

## Dependencies

- Django
- Jinja
- psycopg2
- sqlparse
- virtualenv
- Werkzeug
- whitenoise
- WTForms