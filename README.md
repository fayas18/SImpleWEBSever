# SImpleWEBSever
# EX01 Developing a Simple Webserver
## Date:09-10-2026

## AIM:
To develop a simple webserver to serve html pages and display the Device Specifications of your Laptop.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Import the necessary modules.

### Step 5:
Define a custom request handler.

### Step 6:
Start an HTTP server on a specific port.

### Step 7:
Run the Python script to serve web pages.

### Step 8:
Serve the HTML pages.

### Step 9:
Start the server script and check for errors.

### Step 10:
Open a browser and navigate to http://127.0.0.1:8000 (or the assigned port).

## PROGRAM:
from django.contrib import admin
from django.urls import path
from django.http import HttpResponse

def my_home_page(request):
    name = "S.FAYAS GANI"
    ref_no = "26013026"

    return HttpResponse(
        f"<h1>Name: {name}</h1>"
        f"<p>Register Number: {ref_no}</p>"
    )

urlpatterns = [
    path('admin/', admin.site.urls),
    path('', my_home_page),
]



## OUTPUT:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ae9dbfc1-ef95-4d60-9adb-4284a4286c40" />


## RESULT:
The program for implementing simple webserver is executed successfully.
