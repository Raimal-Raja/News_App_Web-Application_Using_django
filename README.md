# News App Web-Application Using django

Django news web application with templates, application views, and a dependency manifest.

## Setup and repository reference

### Project structure

- [Screenshot 2025-09-01 105514.png](Screenshot%202025-09-01%20105514.png)
- [Web-Application](Web-Application)

### Getting started

```bash
git clone https://github.com/Raimal-Raja/News_App_Web-Application_Using_django.git
cd News_App_Web-Application_Using_django
```

Create and activate a virtual environment, then install the project dependencies:

```bash
python -m venv .venv
# Linux/macOS: source .venv/bin/activate
# Windows PowerShell: .venv\Scripts\Activate.ps1
python -m pip install -r "Web-Application/requirements.txt"
```

Run each Django project from the folder containing its manage.py file:

```bash
cd "Web-Application"
python manage.py check
python manage.py migrate
python manage.py runserver
```

### Configuration and limitations

Run commands from Web-Application and install its requirements.txt. News retrieval depends on gnewsclient and external services; live news fetching was not exercised.

### Validation

Audit: 2026-10-08. Repository structure, setup instructions and description were reviewed. 11 existing Python files passed syntax checks; changed files and new regression tests were checked separately. Django system checks passed. Syntax checks do not establish full runtime correctness. External APIs, live scraping, GUI interaction, notebook training and production deployment were not comprehensively exercised.

### Repository description

The short GitHub description is provided in [REPOSITORY_DESCRIPTION.md](REPOSITORY_DESCRIPTION.md).

### Contributions

Describe the issue, reproduction steps, environment, and expected behavior when proposing a change. Keep generated environments, credentials, and unnecessary build artifacts out of new commits.

### License

No top-level license file was found during this review.
