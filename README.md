# FastPhone

https://user-images.githubusercontent.com/73114430/160243640-d7de6ee6-b3ef-4c0a-b24d-f60d6e4a3a0c.mp4


Fastphone is a python/django-based consumer electronics shop
To run this project in your computer, follow the steps below
-------------------------------------------------------------
Step 1. Make and activate virtual Environment in your computer
    In windows
    > virtualenv ecom
    > Scripts\activate
    In mac and linux
    $ virtualenv ecom
    $ source bin/activate

Step 2. Clone the project
    $ git clone https://github.com/KeroAyad/FastPhone
    $ cd FastPhone-Master
    if you donot have git in your computer, install it before and clone it again.

Step 3: Install dependencies 
    $ pip install -r requirements.txt
    or 
    $ pip install django pillow requests six

Step 4: Apply the migration if any
    $ python manage.py migrate


Step 5: You can now open project folder in your editor

Step 6: Run Development server
    $ python manage.py runserver
