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
basic use case for [djangoec](http://github.com/jdillworth/djangoec).

# Dependencies

* Just Django 1.3.x (earlier versions likely to work, but untested)
* [djangoec](http://github.com/jdillworth/djangoec)

# License

Copyright (c) 2011, Jeremy Dillworth
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

 * Redistributions of source code must retain the above copyright notice, this
 list of conditions and the following disclaimer.
 * Redistributions in binary form must reproduce the above copyright notice,
 this list of conditions and the following disclaimer in the documentation
 and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.


