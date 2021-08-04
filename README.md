# Notes Application

This is a simple notes application that I used to learn how to combine Django and React in a single project. This is as bare bones as can be to provide simplicity for a developer to extend upon.
## Features (already implemented or planned)

- Backend with Django Rest Framework
- Frontend with React 
- Bootstrap for styling
- Deployment with docker-compose on single VPS
- SSL certificate from Let's encrypt
- Authentication with DRF `authtoken` and [Djoser](https://djoser.readthedocs.io/en/latest/)
- python-decuple for secrets
- Step-by-step instructions how to deploy and how to update application

## Step-by-step instructions:
1. Create virual environment and install requirements
> ```
> $git clone https://github.com/addelogan/notes-app.git
> $cd notes-app/backend
> $python3 -m venv venv && source venv/bin/activate
> $pip install -r requirements.txt
> $cd server
> $python manage.py makemigrations
> $python manage.py migrate
> $python manage.py runserver
> ```
2. Install node dependencies
> ```
> $cd notes-app/frontend
> $npm i
> $npm start
> ```
3. View your app at http://localhost:3000/ !