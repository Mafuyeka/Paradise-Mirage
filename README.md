# Paradise Mirage

Paradise Mirage is an Airbnb-like website developed to provide users with a platform to find and book vacation rentals.

## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Description

Paradise Mirage is a web application where users can browse, view, and book vacation rentals. Property owners can list their properties with images, descriptions, and prices.

## Features

- User registration and authentication
- Property listings with images
- Detailed property view
- Booking system (to be implemented)

## Technologies Used

- **Front-End**: HTML, CSS, Bootstrap
- **Back-End**: Python, Flask, SQLAlchemy
- **Database**: SQLite (can be switched to PostgreSQL or other databases)

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

- Python 3.x
- Virtual Environment (optional but recommended)

### Installation

1. **Clone the repo**
    ```sh
    git clone https://github.com/your_username/paradise_mirage.git
    ```
2. **Navigate to the project directory**
    ```sh
    cd paradise_mirage
    ```
3. **Create a virtual environment**
    ```sh
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
4. **Install dependencies**
    ```sh
    pip install -r requirements.txt
    ```
5. **Initialize the database**
    ```sh
    flask shell
    >>> from app import db
    >>> db.create_all()
    >>> exit()
    ```

### Running the Application

1. **Start the Flask application**
    ```sh
    python run.py
    ```
2. **Open your browser and visit**
    ```sh
    http://127.0.0.1:5000/
    ```

## Usage

- Register for an account.
- Browse available properties.
- View property details.
- (Future Feature) Book a property.

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Tshepiso Mafuyeka - [your-email@example.com](mailto:your-email@example.com)

Project Link: [https://github.com/your_username/paradise_mirage](https://github.com/your_username/paradise_mirage)
