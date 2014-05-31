Catalyst
========

Initiated by Kevin Cole (<kjcole@ubuntu.com>) 2014.05.31

This is a Django 1.6 project, using Python 3, initiated at the National
Day of Civic Hacking. See: http://ndoch.codefornova.org/

Specifically, I'm hoping to focus on something for the Department of
Energy's Catalyst initiative with a focus on Solar stuff, after chatting
a bit with Ammar Qusaibaty, (CONTR) (<ammar.qusaibaty@ee.doe.gov>). See:

 * http://catalyst.energy.gov/
 * http://en.openei.org/wiki/Main_Page
 * http://en.openei.org/wiki/Gateway:Solar
 * http://en.openei.org/apps/

Although we're using Django 1.6 at the moment, we may change to a
local instance of Django 1.7. See Jeff's Django 1.7 / Python 3 pages:

 * http://proyectojuanchacon.blogspot.com/2014/05/python-3-django-17-on-ubuntu-1404-day-1.html
 * http://www.openbookproject.net/books/bpp4awd/app_a.html

regarding a user-centric installation of Django 1.7.

Begin with:

    $ cd ~/
    $ django-admin startproject catalyst
    $ cd catalyst
    $ python3 manage.py runserver
    ^C
