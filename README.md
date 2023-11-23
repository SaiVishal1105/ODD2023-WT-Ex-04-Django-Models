# Ex-04-Django-Models
NAME: SAI VISHAL D
REF.NO.: 23013576
# AIM:
To create a Django model.

# DESIGN PROCEDURE:
Django Models

## Step 1: Create django project and app using the following commands:
django-admin startproject mymodels  Python manage.py startapp.
## Step 2: Create a user_profile modals in modal.py

![Alt text](<../Screenshot 2023-11-22 200554.png>)

Add the models in the admin interface using the code in admin.py.

![Alt text](<../Screenshot 2023-11-22 201931.png>)

Write the function based view to render the data from the models to template in view.py.

![Alt text](<../Screenshot 2023-11-22 203059.png>)

Setup the url path for the templates using urls.py

![Alt text](<../Screenshot 2023-11-22 205029.png>)

In settings.py file add the app created.

## Step 3: Now do the migrations process to initiate and save the models

Python manage.py makemigrations Python manage.py migrate create a template user_profiles.html.

![Alt text](<../Screenshot 2023-11-22 205704.png>)

## Step 4: Run the program using the command
Python manage.py runserver 8000
In admin/page you can view the models created anf in the user_profile template page you can see the profile page of the user.

# OUTPUT:
![Alt text](../output.png)

![Alt text](<../Screenshot 2023-11-22 205704.png>)


# RESULT:
Thus the django model created successfully.

