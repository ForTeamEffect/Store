# Onstore on Django

This is a full-fledged online store project developed in Django.
In it, I used ***AJAX requests*** to dynamically update the number of products on the cart page without reloading the page, and I used ***asyncio*** to send messages to the Telegram bot asynchronously, without blocking the main application thread .

# Installation

1. Clone the repository

If you don't use Git, you can simply download the repository source code in a ZIP archive and extract it to your computer.

2. Create a virtual environment and activate it
```
python -m venv venv
for Mac
source venv/bin/activate
or
for Win
source venv/Skripts/activate
```
1. Install dependencies
```
pip install -r requirements.txt
```
4. Create a .env in the project root using the image .env.example

5. Run migrations and load data into the database
```
python manage.py migrate
python manage.py loaddata data.json
```
6. Create a store administrator
```
python manage.py createsuperuser
```
7. Start the server
```
python manage.py runserver
```
Open your browser and go to http://127.0.0.1:8000/admin/. Enter your administrator username and password to log into your store control panel.

# Ready!
You have successfully installed an online store using Django and are ready to start using it!

# Contribution to the project
If you have suggestions for improvement or find a bug, feel free to create an issue, send a pull request, or write directly to the author. Your input is welcome!

# Author
[Diashov Makar] (https://github.com/ForTeamEffect)