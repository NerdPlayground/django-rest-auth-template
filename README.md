# Django REST Application Template
This template adds authentication and authorization functionality to the base [Django REST template](https://github.com/NerdPlayground/django-rest-template) along with a custom user. To implement this template, head over to the base [Django REST template](https://github.com/NerdPlayground/django-rest-template) for the relevant steps. It adds the following;
- Packages;
    - Alluth and Dj Rest Auth - they handle user registration
    - Django Rest Password Reset - handles account retrieval
    - Django Rest Knox - handles user authentication
- Endpoints;
    - Account registration
    - Email confirmation
    - Token based log in/out
    - Password reset/change
    - Current logged in user
    - All registered users
    - Search user by username