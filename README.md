# Inventory Management System

![Django](https://img.shields.io/badge/Django-5.1.1-green)
![Python](https://img.shields.io/badge/Python-3.12-blue)
![License](https://img.shields.io/badge/license-MIT-brightgreen)
![Contributions](https://img.shields.io/badge/contributions-welcome-orange)

This is an Inventory Management System developed using the Django framework. The system allows users to efficiently manage stock, track inventory levels, and generate reports to support decision-making.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Contributing](#contributing)


## Features

- **Product Management:** Add, edit, and delete product details.
- **Stock Tracking:** Monitor stock levels, view stock history, and receive restocking alerts.
- **Reporting:** Generate and export reports related to sales, stock levels, and more.

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/TandohAnthonyNwiAckah/my_inventory.git
    ```
2. **Navigate to the project directory:**
    ```bash
    cd my_inventory
    ```
3. **Install `pipenv` if not already installed:**
    ```bash
    pip install pipenv
    ```
4. **Install dependencies using the `Pipfile.lock`:**
    ```bash
    pipenv install --ignore-pipfile
    ```
    This will ensure that the exact versions specified in the `Pipfile.lock` are installed.

5. **Activate the virtual environment:**
    ```bash
    pipenv shell
    ```
6. **Run database migrations:**
    ```bash
    python manage.py migrate
    ```
7. **Create a superuser account:**
    ```bash
    python manage.py createsuperuser
    ```
8. **Start the server:**
    ```bash
    python manage.py runserver
    ```


## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new feature branch (`git checkout -b feature/new-feature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Open a pull request.

