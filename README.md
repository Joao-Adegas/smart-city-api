# Smart City API

Django backend of the **Smart City** platform, which manages sensors, environments and historical data for smart urban spaces. It gives full CRUD control over data such as temperature, humidity, luminosity and people count.

> Dashboard: [smart-city-web](https://github.com/Joao-Adegas/smart-city-web)

## Features

- CRUD for sensors
- CRUD for environments
- Historical data for each sensor (temperature, humidity, luminosity, people count)
- Django admin for administration

## Tech stack

Python, Django

## Getting started

### Prerequisites

- Python 3

### Run

```bash
python -m venv env

# Windows
./env/Scripts/activate
# macOS / Linux
source env/bin/activate

pip install -r requirements.txt

# Apply migrations
python manage.py makemigrations
python manage.py migrate

# Create an admin user
python manage.py createsuperuser

# Start the server
python manage.py runserver
```

The API will be available at `http://127.0.0.1:8000`.

## Author

João Pedro dos Santos Adegas — [@Joao-Adegas](https://github.com/Joao-Adegas)
