# Flask Authentication App

Welcome to the **Flask Authentication App**! This is a simple web app built using **Flask**, providing a login and registration system with encrypted passwords. It's designed to demonstrate basic authentication workflows in a Python web application.

## Table of Contents
- [Description](#description)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Description

This project is a **Flask**-based web application that allows users to register, log in, and manage authentication. It includes features such as:
- User registration and login system
- Password hashing and authentication using **Flask-Bcrypt**
- Session management with **Flask-Login**
- Simple, clean interface for login and registration

## Technologies Used

- **Python** (Flask)
- **HTML**, **CSS** for frontend
- **SQLite** for database
- **Flask-SQLAlchemy** for ORM (Object-Relational Mapping)
- **Flask-Bcrypt** for password hashing
- **Flask-Login** for session management

## Installation

### Prerequisites

To get the project running, you’ll need to have the following installed:
- **Python 3.x**: [Download Python](https://www.python.org/downloads/)
- **Pip**: Package installer for Python

### Steps to Set Up the App:

1. Clone the repository:
   ```bash
   git clone https://github.com/fwesh001/flask-auth-demo.git


2. Navigate to the project folder:

   ```bash
   cd flask-auth-demo
   ```
3. Create a virtual environment (optional but recommended):

   ```bash
   python -m venv .venv
   ```
4. Activate the virtual environment:

   * For Windows:

     ```bash
     .\.venv\Scripts\Activate
     ```
   * For macOS/Linux:

     ```bash
     source .venv/bin/activate
     ```
5. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
6. Set up the database:

   ```bash
   flask db init
   flask db migrate
   flask db upgrade
   ```
7. Run the application:

   ```bash
   python app.py
   ```

   The app should now be running at `http://127.0.0.1:5000`.

## Usage

Once the app is running, you can:

* **Register** a new user by navigating to `/register`
* **Login** using your credentials at `/login`
* Visit the **dashboard** after logging in

## Contributing

Feel free to fork the repository and create a pull request! Contributions are always welcome. Please make sure to follow these steps when contributing:

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to your fork
5. Create a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Thanks for checking out my project! Feel free to ask questions or suggest improvements. 😊

