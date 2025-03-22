# Learning Log

A web application that allows users to track their learning progress by adding topics and logging their learning activities.

## Features
- User authentication (sign up, log in, log out)
- Add, edit, and delete learning topics
- Create and update learning entries under each topic
- Secure access so users can only modify their own entries

## Installation

### Prerequisites
- Python 3.10+
- Django 4+
- Bootstrap5
- Platform
- Gunicorn
- Virtual environment (recommended)

### Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/pablo727/learning_log.git
   cd learning_log
   ```

2. Create and activate a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

4. Apply database migrations:
   ```sh
   python manage.py migrate
   ```

5. Create a superuser (for admin access):
   ```sh
   python manage.py createsuperuser
   ```

6. Run the development server:
   ```sh
   python manage.py runserver
   ```
   The application will be available at `http://127.0.0.1:8000/`.

## Usage
- Navigate to the homepage and create an account.
- Add topics related to what you're learning.
- Log your progress by adding learning entries.
- View, edit, or delete your entries as needed.

## Contributing
Pull requests are welcome! If you find any issues or want to contribute, feel free to submit a PR or open an issue.

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
