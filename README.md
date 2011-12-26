# Intro

Minimal PayPal is a shell project for djangoec (Django Express Checkout).

# Installation

Create a database:

    $ ./manage.py syncdb

Create an api-keys.txt file with contents something like this (the separate
file is used so committing to minimalpaypal will not commit your keys):

    [api]
    PAYPAL_USERNAME=some_guy@example.com
    PAYPAL_API_USERNAME=some_guy_biz_api1.example.com
    PAYPAL_API_PASSWORD=1116987378
    PAYPAL_API_SIGNATURE=AIc8kLdsLeV6YhXX7m7PNnK2ucPRAFxh1hMLKJ4T30G1l1NxVGVGqfSd

Run the server:

    $ ./manage.py runserver

You should now be able to open up http://localhost:8000/ and try out a super
basic use case for djangoec.

# Dependencies

* Just Django 1.3.x (earlier versions likely to work, but untested)
* [djangoec](http://github.com/jdillworth/djangoec)

