# Temuge Photocopy & Cyber Café Website

A Django-based business website for **Temuge Photocopy & Cyber Café**, a cyber café and photocopy business located in Sosiot. The website presents the business services, prices, contact details, WhatsApp link, Google Maps directions, and call-to-action buttons for customers.

## Project Overview

This website helps customers quickly understand the services offered by Temuge Photocopy & Cyber Café and easily contact or visit the business.

The main goal of the website is to convert online visitors into real customers by making services, prices, location, and contact options clear.

## Features

* Clean and responsive homepage
* Business services section
* Price guide section
* About section
* Contact section
* WhatsApp button
* Google Maps direction button
* Call button
* Mobile-friendly layout
* Django static files setup
* Smooth page scrolling

## Services Included

The website highlights services such as:

* Printing and photocopying
* KRA PIN services
* eCitizen services
* HELB services
* Online applications
* Typing and document editing
* Lamination and binding
* Computer support
* Internet browsing assistance

## Technologies Used

* HTML
* CSS
* Python
* Django

## Project Structure

```txt
temuge_site/
│
├── business/
│   ├── migrations/
│   ├── static/
│   │   └── business/
│   │       └── css/
│   │           └── style.css
│   ├── templates/
│   │   └── index.html
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
│
├── temuge_site/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── manage.py
├── requirements.txt
├── .gitignore
└── README.md
```

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/temuge-cyber-website.git
```

### 2. Enter the project folder

```bash
cd temuge-cyber-website
```

### 3. Create a virtual environment

```bash
python -m venv .venv
```

### 4. Activate the virtual environment

For Windows PowerShell:

```bash
.venv\Scripts\Activate
```

For Linux or macOS:

```bash
source .venv/bin/activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Run migrations

```bash
python manage.py migrate
```

### 7. Start the development server

```bash
python manage.py runserver
```

Open the website in your browser:

```txt
http://127.0.0.1:8000/
```

## Static Files

The CSS file is located at:

```txt
business/static/business/css/style.css
```

The template loads the CSS using:

```django
{% load static %}
<link rel="stylesheet" href="{% static 'business/css/style.css' %}">
```

## Contact Information Used

```txt
Business Name: Temuge Photocopy & Cyber Café
Location: Sosiot
Phone: +254 789 310 275
WhatsApp: +254 789 310 275
Opening Hours: Monday - Saturday, 8:00 AM - 6:00 PM
```

## Git Workflow

After making changes, use:

```bash
git status
git add .
git commit -m "Update website"
git push
```

## Important Notes

Do not upload sensitive files such as `.env` to GitHub.

Recommended `.gitignore` entries:

```gitignore
.venv/
venv/
env/

__pycache__/
*.pyc

.env
db.sqlite3

.vscode/
```

## Future Improvements

Possible improvements for the website include:

* Add customer reviews
* Add photo gallery
* Add service request form
* Add admin-managed services and prices
* Add separate pages for major services
* Add SEO blog posts for cyber services in Sosiot

## License

This project is for Temuge Photocopy & Cyber Café. All rights reserved.
