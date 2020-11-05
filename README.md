# cookiecutter-django-heroku

Cookiecutter script from [pydanny](https://github.com/pydanny/cookiecutter-django) to setup Django with PostgresQL for Heroku deployment. Cookiecutter Django Heroku is a CLI based on [Cookiecutter](https://github.com/cookiecutter/cookiecutter) and an easy way to get projects into production using templates.  
  
## Features  

- For Django 3.0
- Works with Python 3.8
- Renders Django projects with 100% starting test coverage
- Twitter Bootstrap v4 (maintained Foundation fork also available)
- 12-Factor based settings via django-environ
- Secure by default. We believe in SSL.
- Optimized development and production settings
- Registration via django-allauth
- Comes with custom user model ready to go
- Optional basic ASGI setup for Websockets
- Optional custom static build using Gulp and livereload
- Send emails via Anymail (using Mailgun by default or Amazon SES if AWS is selected cloud provider, but switchable)
- Media storage using Amazon S3 or Google Cloud Storage
- Docker support using docker-compose for development and production (using Traefik with LetsEncrypt support)
- Procfile for deploying to Heroku
- Instructions for deploying to PythonAnywhere
- Run tests with unittest or pytest
- Customizable PostgreSQL version
- Default integration with pre-commit for identifying simple issues before submission to code review  

## Optional Integrations
*These features can be enabled during initial project setup.*

- Serve static files from Amazon S3, Google Cloud Storage or [Whitenoise](https://whitenoise.readthedocs.io/)  
- Configuration for [Celery](http://www.celeryproject.org/) and [Flower](https://github.com/mher/flower) (the latter in Docker setup only)  
- Integration with [MailHog](https://github.com/mailhog/MailHog) for local email testing  
- Integration with [Sentry](https://sentry.io/welcome/) for error logging  

## Constraints
- Only maintained 3rd party libraries are used.
- Uses PostgreSQL everywhere (9.4 - 12.3)
- Environment variables for configuration (This won't work with Apache/mod_wsgi).

## Support this Project!

The project is run by volunteers. Please support them in their efforts to maintain and improve [Cookiecutter Django](https://github.com/pydanny/cookiecutter-django)
