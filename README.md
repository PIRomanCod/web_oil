#Архітектура

Django (admin + data)  -->  python manage.py runserver
        ↓
django-distill   --> python manage.py collectstatic     python manage.py distill-local dist
        ↓
Static site
        ↓
GitHub Pages / CDN


Після змін у dist з’явиться:

dist
 ├ index.html
 ├ products/index.html
 ├ news/index.html
 ├ team/index.html
 ├ contacts/index.html
 └ static/


Правильна архітектура для твого сайту
Domain
│
├── Website
│     GitHub Pages / CDN
│
├── Email
│     Google Workspace
│
└── DNS
      Cloudflare


Usefull:

pip install django

django-admin startproject prooil_site

cd prooil_site

python manage.py startapp public

python manage.py startapp dashboard

python manage.py startapp accounts

python manage.py migrate

python manage.py runserver

http://127.0.0.1:8000

python manage.py createsuperuser

http://127.0.0.1:8000/admin

