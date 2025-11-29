# Ex01 Django ORM Web Application
## Date: 27.11.2025

## AIM
To develop a Django application to store and retrieve data from a Car Inventory Database using Object Relational Mapping(ORM).

## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create details for 5 Car 

## PROGRAM
```
models.py

from django.db import models

from django.contrib import admin

# Create your models here.

class Book(models.Model):

book_name = models.CharField(max_length-20, help_text="Enter Book Name")

prize models. IntegerField(help_text="Enter prize between 500-1500")

author_name = models.CharField(max_length-20, help_text="Enter Author Name")

class BookAdmin(admin.ModelAdmin):

list_display= ['book_name', 'prize', 'author_name']

admin.py

from django.contrib import admin

from.models import Book, BookAdmin

admin.site.register(Book, BookAdmin)
```
## OUTPUT
<img width="1600" height="809" alt="image" src="https://github.com/user-attachments/assets/3d812bf1-006e-41e3-b387-31607f2ad589" />


## RESULT
Thus the program for creating car inventory database database using ORM hass been executed successfully
