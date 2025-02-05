# Moscow Time Django Web Application

## Overview

This Django web application provides an API endpoint that returns the current time in Moscow. It uses the `Django` framework along with the `pytz` library for handling time zones.

## Features

- Provides a RESTful API endpoint to retrieve the current Moscow time.
- Follows best practices for Django web application development.

## Getting Started

### Prerequisites

- Python 3.x
- `Django` framework
- `pytz` library

### Installation

1. Create and activate a virtual environment:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: .\venv\Scripts\activate
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

### Usage

1. Run the Django development server:

    ```bash
    python manage.py runserver
    ```

2. Access the Moscow time API endpoint:

    - URL: http://localhost:8000/moscow-time/
    - Method: GET
    - Response: JSON object containing the current Moscow time.

### Example Response

```json
{
  "moscow_time": "2024-02-05 12:34:56 MSK"
}