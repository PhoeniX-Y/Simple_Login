# Flask User Authentication App

A simple Flask web application with user authentication features including registration, login, and a protected dashboard.

## Features

- User registration with email verification
- Secure login system
- Password hashing
- Protected dashboard
- Remember me functionality
- Flash messages for user feedback

## Installation

1. Clone the repository
```sh
git clone <your-repository-url>
cd Simple-app
```

2. Create a virtual environment and activate it
```sh
python -m venv myenv
source myenv/bin/activate  # On Windows use: myenv\Scripts\activate
```

3. Install dependencies
```sh
pip install -r requirements.txt
```

4. Set up environment variables
```sh
# Create a .env file with:
SECRET_KEY=your_secret_key_here
DATABASE_URL=sqlite:///site.db
```

5. Initialize the database
```sh
python app.py
```

## Usage

Run the development server:
```sh
python app.py
```

Visit `http://localhost:5000` in your web browser.

## Project Structure

```
├── app.py              # Main application file
├── requirements.txt    # Project dependencies
├── static/            # Static files
│   ├── css/
│   │   └── style.css
│   └── main.js
└── templates/         # HTML templates
    ├── base.html
    ├── home.html
    ├── login.html
    ├── register.html
    └── dashboard.html
```