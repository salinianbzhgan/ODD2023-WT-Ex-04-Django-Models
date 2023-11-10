# Ex-04-Django-Models
Name: Salini. A

Reg No:23008741

Dept: IT

# AIM:
To create a django model with five users.

1.setting email address for all users.

2.setting first name and last name for all users.

# Design procedure
# Step1 : Create django project and app using the following commands:
Django-admin startproject mymodels

Python manage.py startapp myapp

# Step 2: create a user_profile models in model.py
Add the models in the admin interface using the code in admin.py

# Step 3: define user creation view
Write the function based view to render the data from the models to the template in view.py

# Step 4: Setup the url
Setup the url path for the templates using urls.py

In settings.py file add the app created.

# Step 5: Create template
Create a template as user_profiles.html

# Step 6: Apply migrations
Now do the migrations process to initiate and save the models

python manage.py makemigrations

python manage.py migrate

# Step 7: Run the program
Run the program using the command

Python manage.py runserver 8000

In the admin/ page you can view the models created

And in the user_profile template page you can see the profile page of the user.

# Output
![Screenshot 2023-11-10 110228](https://github.com/salinianbzhgan/ODD2023-WT-Ex-04-Django-Models/assets/145742862/2664bb56-11a2-4568-b541-0f3347120320)

