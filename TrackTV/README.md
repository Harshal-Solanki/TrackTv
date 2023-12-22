## Project Title
TrackTV

## Group Roll Numbers
UI20EC20- Harshal Solanki
UI20EC17- Daivik Padmanabhan

## TrackTV
TrackTV is a website created using Python, Django to allow users to track TV shows they have seen. All data is obtained using [TVmaze API](http://www.tvmaze.com/api).

## Required modules
- Crispy Forms
- requests
- Beautiful Soup
- lxml

## Features
- Simply rate the show to add it on your list.
- A list page to list all your shows with your ratings.
- A profile page with info, top 5 shows, etc.

## Installion Guide
- Extract the zip file.
- Install the required modules mention above.
- Create a Superuser. (Command - python manage.py createsuperuser)
- Make Migrations. (Command- python manage.py migrate)
- Run the Django Project. (Command- python manage.py runserver)
- After running project add '/admin' to URL and Login to Admin Page. (The Same username and password with which super user is created in above step)
- After Logging in to Admin Page Return back to home page and you are ready to use the website.