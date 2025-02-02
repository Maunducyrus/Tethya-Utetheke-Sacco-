# Sacco Management System

A web application designed to manage savings, loans, and member information for a Sacco (Savings and Credit Cooperative Organization). Built using **Django** for the backend and **React with Bootstrap** for the frontend, this platform provides an efficient way for members to access financial services.

## Features

- **User Authentication**: Secure login and registration system.
- **Member Dashboard**: View account details, savings, and loan status.
- **Loan Management**: Apply for loans and track repayment progress.
- **Savings Management**: Monitor deposits and withdrawals.
- **Admin Panel**: Manage users, approve loans, and view reports.
- **Responsive Design**: Mobile-friendly UI using Bootstrap.

## Tech Stack

- **Frontend**: React, Bootstrap
- **Backend**: Django, Django REST Framework
- **Authentication**: Django Authentication

## Backend Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/sacco-website.git
   cd sacco-website/backend
   ```

2. **Create and activate a virtual environment:**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

4. **Run database migrations:**
   ```sh
   python manage.py migrate
   ```

5. **Start the development server:**
   ```sh
   python manage.py runserver
   ```

## Usage

- Visit **[http://127.0.0.1:8000](http://127.0.0.1:8000)** for the backend API.
- Visit **[http://localhost:3000](http://localhost:3000)** for the frontend UI.

## Contribution

1. **Fork the repository.**
2. **Create a feature branch:**
   ```sh
   git checkout -b feature-branch
   ```
3. **Commit your changes:**
   ```sh
   git commit -m 'Add new feature'
   ```
4. **Push to your branch:**
   ```sh
   git push origin feature-branch
   ```
5. **Create a pull request.**

## License

This project is licensed under the **MIT License**.

## Contact

For inquiries, reach out via **maunducyrus123@gmail.com**.
