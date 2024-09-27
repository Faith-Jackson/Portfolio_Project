# VogueNest

Welcome to **VogueNest** – an e-commerce platform that offers users a seamless shopping experience, from browsing the latest trends to purchasing their favorite fashion items. This project is part of our **ALX Foundation Portfolio** and aims to qualify our team for specialization.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Technologies](#technologies)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Contributors](#contributors)
7. [License](#license)

## Project Overview
**VogueNest** is an innovative e-commerce platform designed to allow users to explore a wide variety of fashion products. Whether you're looking for the latest trends or timeless classics, VogueNest provides an intuitive and user-friendly platform to shop from.

## Features
- User authentication and profile management.
- Product catalog with detailed item descriptions and reviews.
- Shopping cart and secure checkout process.
- Admin dashboard for managing products and orders.
- Search and filter functionality for ease of product discovery.
- Mobile-friendly design for a seamless experience on all devices.

## Technologies
- **Frontend**: Bootstrap for styling and responsiveness.
- **Backend**: Django (Python framework) for web development.
- **Database**: SQLite (default Django database).
- **Version Control**: Git & GitHub.
- **Hosting**: Heroku.
- **API Integration**: Paypal.

## Installation
To set up the project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/faith-jackson/Porfolio_Project.git
    ```

2. Navigate to the project directory:
    ```bash
    cd VogueNest
    ```

3. Create a virtual environment:
    ```bash
    python3 -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

4. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

5. Set up environment variables:
    Create a `.env` file in the root of the project and add your configuration (e.g., database settings, secret key).

6. Apply migrations to set up the database:
    ```bash
    python manage.py migrate
    ```

7. Create a superuser to access the Django admin panel:
    ```bash
    python manage.py createsuperuser
    ```

8. Start the development server:
    ```bash
    python manage.py runserver
    ```

9. Open your browser and go to:
    ```bash
    http://localhost:8000
    ```

## Usage
Once the project is installed and running, users can:
- Sign up and log in to their account.
- Browse fashion categories and add products to their shopping cart.
- Complete the checkout process with payment integration.
- Review their order history and manage personal profiles.

Admins can:
- Add, edit, or remove products.
- View and manage user orders.
- Access the admin dashboard for sales analytics.

## Contributors
This project is a collaboration between:
- [Faith Jackson](https://github.com/faith-jackson)
- [Anieyie Asuquo](https://github.com/anieyie-asuquo)


## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE.txt) file for details.