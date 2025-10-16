🧑‍💻 Darshan M S – Developer Portfolio

This repository contains my personal portfolio website developed using Django, HTML5, CSS3, and JavaScript.
It showcases my projects, skills, and experience as a front-end developer passionate about creating elegant, responsive, and high-performance web applications.

🚀 Features

🎨 Responsive Design – Works smoothly across all devices (mobile, tablet, desktop).

⚡ Dynamic Sections – Projects, Skills, About Me, and Contact Form integrated with Django templates.

🌗 Light/Dark Mode – User-friendly theme toggle for better accessibility.

🔍 Project Filtering & Search – Explore projects by category (Web, UI, JS).

📬 Contact Form Layout – Structured and ready for backend email handling or API integration.

🧱 Clean Code Structure – Organized templates and static files for easy maintenance and scalability.

🛠 Tech Stack

Frontend: HTML5, CSS3, JavaScript 
Backend: Python
Web frameworks : Django
Tools: VS Code, Git, Python 3.12
Version Control: Git & GitHub

🧩 Highlights

💡 Built with Django’s template system for efficient static file management.
🎯 Designed from scratch with custom CSS, ensuring fast load times and smooth transitions.
🧑‍💻 Showcases real-world front-end development practices with modern styling and usability focus.
🧾 Includes clear structure for future scalability and feature integration.

📈 Future Improvements

🚧 Add backend integration for the contact form.
📝 Include a blog section with Django models.
🌐 Deploy to cloud hosting platforms (Render, Vercel, or PythonAnywhere).
🔎 Enhance SEO and analytics tracking.

🧩 Development Process

Here’s the complete process followed to design and build this portfolio:

⿡ Project Setup

Installed Python 3.12 and Django framework using

#pip install django


Created a new Django project:

#django-admin startproject portfolio


Added a new Django app for portfolio sections:

#python manage.py startapp main

⿢ Project Configuration

Add import os in Setting.py @top

Registered the app (main) in settings.py under INSTALLED_APPS.
#INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'app' -->Here 
]

Configured STATICFILES_DIRS and TEMPLATES directories for easy access to HTML and CSS files.
#STATICFILES_DIRS = [
    os.path.join(BASE_DIR, 'app', 'static'),
]

Set up the project’s urls.py and included app-level URLs for modular navigation.
from django.contrib import admin
from django.urls import path
from app import views -->Import and include sub apps/views here.

urlpatterns = [
    path('admin/', admin.site.urls),
    #add views router along with function names here 
]

⿣ Template & Static File Integration

Created reusable templates ( index.html).
#optional -->you can create it as Multi Html pages like(Home.html,Project.html ..ect)
Linked static files using Django’s {% load static %} tag.

Integrated CSS3 for responsive design and JavaScript for interactivity.

⿤ Portfolio Sections

Home Page: Added a professional introduction with name, title, and dynamic background.

About Me: Highlighted education, role at AdminDroid, and technology expertise.

Projects: Displayed Django, Python, and AI-based works (e.g., Healthcare Chatbot, Doctor Recommendation System).

Skills: Represented technical strengths in Python, Django , Sql and Web Development.

Contact Form: Designed an interactive layout with placeholders for email backend integration.

⿥ Frontend Enhancements

Implemented light/dark mode toggle using JavaScript and CSS variables.

Added hover animations and smooth transitions for UI elements.

Optimized layout with Flexbox and Grid for responsive alignment.

⿦ Version Control

Initialized a local Git repository:

git init
git add .
git commit -m "Initial portfolio setup"


Pushed the project to GitHub for version tracking and showcasing.

⿧ Testing & Optimization

Tested across devices (mobile, tablet, desktop) for full responsiveness.

Validated all HTML and CSS using W3C validators.

Minified assets and improved page load performance.

⿨ Deployment (Upcoming)

Preparing deployment using Render or Vercel with Django backend.

Future plan to integrate domain name and SSL for production-level hosting.

🏁 Outcome

This portfolio demonstrates:

Strong command of Django and frontend technologies

Ability to build end-to-end responsive web applications

A clear presentation of skills, certifications, and projects

🏆 Certifications & Acknowledgements
🎓 Certifications
•	PEGA – SENIOR SYSTEM ARCHITECT(2023 - 2024)
•	JAPANESE - N5 LEVEL(2024)
•	STEP COURSE (2023)
👩‍💻 Author Information
DARSHAN M S 
🎓BTECH, M.KUMARASAMY COLLEGE OF ENGINEERING
💼 Python Fullstack Trainee
📚 SENIOR SYSTEM ARCHITECT
🔧 Tools And Technologies: Python, PEGA,  django , numpy , FLASK    




