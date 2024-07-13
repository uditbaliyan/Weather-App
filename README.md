

# Weather App

A simple Django application that fetches and displays weather information using an API.

## Features

- Fetches weather information based on user input.
- Displays current temperature, weather conditions, and more.
- User-friendly interface with a clean design.

## Installation

Follow these steps to set up and run the project locally.

### Prerequisites

- Python 3.x
- pip
- Django
- Requests

### Clone the Repository

```bash
git clone https://github.com/uditbaliyan/Weather-App.git
cd Weather-App
```

### Set Up Virtual Environment

It's a good practice to use a virtual environment to manage dependencies. You can create one using `venv`.

```bash
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Set Up Environment Variables


### Run Migrations

```bash
python manage.py migrate
```

### Run the Server

```bash
python manage.py runserver
```

Navigate to `http://127.0.0.1:8000` in your browser to see the application in action.

## Usage

1. Enter the city name in the input field.
2. Click on the "Get Weather" button.
3. The app will fetch and display the current weather information for the specified city.




