
# Online Movie Ticket Booking System

A web-based movie ticket booking application built using Python, Flask, SQLite, and SQL. It provides user authentication, movie listings, theater management, and administrative CRUD operations.

## Features

- User registration, login, and logout
- Secure password hashing
- Movie listing and management
- Add, view, update, and delete movies
- Theater management across multiple cities
- Add, view, update, and delete theaters
- Admin dashboard
- SQLite database with relational tables

## Tech Stack

- **Backend:** Python, Flask
- **Database:** SQLite, SQL
- **Frontend:** HTML, CSS
- **Security:** Werkzeug Password Hashing

## Project Structure

```text
MovieBookingSystem/
├── app.py
├── database.py
├── requirements.txt
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── movies.html
│   └── admin.html
├── static/
│   ├── style.css
│   └── images/
└── .gitignore
```

## Installation and Setup

**1. Clone the repository**

```bash
git clone <repository-url>
cd MovieBookingSystem
```

**2. Create and activate the environment**

```bash
conda create -n moviebooking python=3.11 -y
conda activate moviebooking
```

**3. Install dependencies**

```bash
pip install -r requirements.txt
```

**4. Configure admin email**

```bash
set ADMIN_EMAIL=your_email@gmail.com
```

**5. Initialize the database**

```bash
python database.py
```

**6. Run the application**

```bash
python app.py
```

**7. Open in browser**

```text
http://127.0.0.1:5000
```

## Database Tables

- Users
- Movies
- Theaters
- Shows
- Seats
- Bookings
- Feedback

## Future Enhancements

- Interactive seat selection
- Real-time seat availability
- Movie show scheduling
- Online ticket booking
- Email booking confirmations
- Booking history
- User feedback and ratings
