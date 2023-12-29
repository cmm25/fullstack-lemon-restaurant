# Little Lemon Capstone Project

## Project Overview

This is a capstone project for the Backend Engineering on Coursera. The goal is to develop a RESTful API for LittleLemon Restaurant, which will be used to manage the restaurant's menu and orders. The API is developed using Python and Django Rest Framework, with MySQL as the database.

## Getting Started

### Prerequisites

- Python 3.6 or higher
- Django 3.0 or higher
- Django Rest Framework 3.11 or higher
- MySQL 12.1 or higher

### Installation

1. Clone the repo

   ```bash
   git clone https://github.com/aniebietafia/LittleLemon-Capstone-Project.git
   ```

2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```

3. Create a database in MySQL

   ```sql
   CREATE DATABASE littlelemon;
   ```

4. Create a `.env` file in the root directory and add the following environment variables

   ```env
   SECRET_KEY=your_secret_key
   DEBUG=True
   DB_NAME=littlelemon
   DB_USER=your_db_user
   DB_PASSWORD=your_db_password
   DB_HOST=your_db_host
   DB_PORT=your_db_port
   ```

5. Run migrations

   ```bash
   python manage.py migrate
   ```

6. Run the server

   ```bash
   python manage.py runserver
   ```

7. Run tests

   ```bash
   python manage.py test
   ```

## API Reference

### Menu Endpoints

- **GET** `/api/menu/`: Get all menu items
- **POST** `/api/menu/`: Create a new menu item
- **GET** `/api/menu/{id}/`: Get a menu item by id
- **PUT** `/api/menu/{id}/`: Update a menu item by id
- **DELETE** `/api/menu/{id}/`: Delete a menu item by id

### Booking Endpoints

- **GET** `/api/booking/`: Get all bookings
- **POST** `/api/booking/`: Create a new booking
- **GET** `/api/booking/{id}/`: Get a booking by id

## About

Capstone Project for the Little Lemon API using Django framework and MYSQL.

## Best Practices

1. **Documentation and Comments:**
   - Add detailed comments in your code, especially in complex sections.
   - Document the purpose and usage of each API endpoint.

2. **Database Configuration:**
   - Ensure MySQL server is properly configured and running before migrations.

3. **Security:**
   - Keep `SECRET_KEY` and database credentials secure.
   - Consider using environment variables directly in the server environment.

4. **Testing:**
   - Thoroughly test all aspects of your API.

5. **Error Handling:**
   - Implement proper error handling with meaningful messages and status codes.

6. **Authorization and Authentication:**
   - Implement user authentication and authorization if needed.

7. **Validation:**
   - Add input validation for API requests.

8. **Logging:**
   - Implement logging for important events or errors.

9. **User-Friendly Responses:**
   - Ensure API returns user-friendly responses.

10. **Documentation:**
    - Create thorough API documentation.

11. **Continuous Integration:**
    - Set up a CI pipeline to run tests automatically.

12. **Versioning:**
    - Consider versioning your API from the beginning.

Remember to keep your README updated as the project progresses and consider adding a license file.

© 2023 GitHub, Inc.
```

