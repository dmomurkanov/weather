# Weather Forecast Application

This application allows users to get the weather forecast for a city. 

## Features

- User authentication
- Weather forecast using Open-Meteo API
- Search history
- API for search history
- Autocomplete for city names
- Docker containerization
- PostgreSQL database
- Unit tests

## Setup

1. Clone the repository:
    ```bash
    git clone <repository-url>
    cd test_project
    ```

2. Create and start the Docker containers:
    ```bash
    docker-compose up --build
    ```

3. Create a superuser:
    ```bash
    docker-compose exec web python manage.py createsuperuser
    ```

4. Open your browser and go to `http://localhost:8000`.

## Usage

- Register and log in.
- Enter a city name to get the weather forecast.
- View your search history.
- Use the API to get search history data.

## Technologies

- Django
- Django REST Framework
- Docker
- PostgreSQL
- Open-Meteo API
