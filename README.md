# Expense Watcher - Built with Django

The Expense Watcher App is a simple, user-friendly application built with Django to help users track and manage their daily expenses. It allows users to add, categorize, and review their spending history while providing insights through monthly or yearly reports. With user authentication, secure data storage, and a clean interface, this app makes budgeting easier. Ideal for anyone looking to monitor their finances efficiently.

## Features

- User authentication (Login/Signup)
- Add, update, and delete expenses
- Categorize expenses (e.g., food, travel, utilities, etc.)
- Generate monthly or yearly reports
- View expense history and trends

## Tech Stack

- Frontend: HTML, CSS, JavaScript 
- Backend: Django
- Database: SQLite
- Other Tools: Django Rest Framework

## Installation

- **Clone the repo**
git clone https://github.com/yourusername/expense-tracker.git

- **Change to the project directory**
cd expense-tracker

- **Install dependencies**
pip install -r requirements.txt

- **Make migrations and migrate the database**
python manage.py makemigrations
python manage.py migrate

- **Create a superuser (for admin access)**
python manage.py createsuperuser

- **Run the development server**
python manage.py runserver

## Usage

Once the app is running, you can access the site at http://localhost:8000. Create an account to start adding your expenses, categorize them, and monitor your spending trends. Admin users can manage categories and view all expense records.

## Contributing

Contributions to this project are welcome. If you have suggestions for improvements or encounter any issues, please feel free to submit a pull request or open an issue in the repository.

## License
The code and resources in this repository are provided under the [MIT License](LICENSE).

## Contact Information

Created by [Mahendra Yadav] - [mahendrayadav5421@gmail.com]


