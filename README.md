# Resume Builder

A simple web application for creating and managing resumes using Python and Django.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- User authentication (sign up, log in, log out)
- Create, edit, and delete resumes
- Download resumes in PDF format
- Responsive design for various devices
- Save multiple resume templates
- Preview resumes before downloading

## Technologies

- **Python**: The programming language used.
- **Django**: The web framework for building the application.
- **HTML/CSS**: For structuring and styling the web pages.
- **Bootstrap**: For responsive design.
- **SQLite**: Default database for development (can be switched to PostgreSQL or others).

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/resume-builder.git
   cd resume-builder
Set up a virtual environment:

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the required packages:
pip install -r requirements.txt

Apply migrations:

python manage.py migrate
Run the development server:


python manage.py runserver
Open your browser and go to:

http://127.0.0.1:8000/


Usage
Create an account or log in to your existing account.
Use the dashboard to create a new resume.
Fill out the required information and choose a template.
Preview your resume and download it in PDF format when you're satisfied.
Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature/YourFeature).
Make your changes and commit them (git commit -m 'Add some feature').
Push to the branch (git push origin feature/YourFeature).
Create a new Pull Request.
