Архітектура

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
