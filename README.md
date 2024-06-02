# Callback Agenda

Callback Agenda is a web application designed to schedule, manage, and track callbacks with features like calendar integration, user authentication, and web push notifications.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript, React
- **Backend**: Python (Django)
- **Database**: PostgreSQL
- **Authentication**: JWT (JSON Web Tokens)
- **Notifications**: Web push notifications (Google Chrome notifications)
- **Calendar Integration**: Google Calendar API

## Project Structure

```plaintext
frontend/
└── index.html
└── styles.css
└── app.js
backend/
└── manage.py
└── callback_agenda/
    └── __init__.py
    └── settings.py
    └── urls.py
    └── wsgi.py
└── api/
    └── __init__.py
    └── urls.py
    └── views.py
└── authentication/
    └── __init__.py
    └── urls.py
    └── views.py
└── notifications/
    └── __init__.py
    └── urls.py
    └── views.py
