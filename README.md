# User Authentication with Email OR Username in Django

This is a simple Django web application that provides user authentication using both username and email.


## Objective

Create a Django web application with user authentication features, including user registration, login, basic user profile, and logout.

## Requirements

- [x] Use Django to create a new project and a single app. 
- [x] Implement a user registration (sign-up) page with the following fields:
   - Username
   - Email
   - Password
   - Confirm Password
- [x] Implement a user login page with the following fields: 
   - Username or Email
   - Password
- [x] After successful login, redirect the user to a simple dashboard page that displays a welcome message with their username.
- [x] Implement a basic user profile page that displays user information. Users should only be able to access this page if they are logged in.
- [x] Implement a logout functionality that logs the user out and redirects them to the login page.
- [x] Use Django's built-in authentication system for handling user registration, login, and logout.

##Screenshots

![image](https://github.com/user-attachments/assets/35d711a4-ed05-4171-8516-ef98fb4b8a9f)
![image](https://github.com/user-attachments/assets/16d1a2e1-ecd6-4bbd-93e0-afa583b8caaa)
![image](https://github.com/user-attachments/assets/81c42af8-ecc0-4c39-a86d-32c9c2099947)


  
## Setup and Run

0. (Optional) Activate a virtual environment to isolate dependencies.

```bash
pip install virtualenv
python -m virtualenv venv
venv/Scripts/activate (Windows)
```

1. Clone the repository:

```bash
git clone 
cd custom-user-django
```
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Apply Migrations:

```bash
python manage.py migrate
```

4. Run the development server:

```bash
python manage.py runserver
```

5. Visit [localhost:8000](https://localhost:8000) in browser to access the application.

