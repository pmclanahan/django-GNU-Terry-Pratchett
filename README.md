Django GNU Terry Pratchett
==========================

Keeping the legacy of [Sir Terry Pratchett](http://en.wikipedia.org/wiki/Terry_Pratchett) alive forever.
For as long as his name is still passed along the Clacks,
Death can't have him.

* G: send the message on
* N: do not log the message
* U: turn the message around at the end of the line and send it back again

with thanks to [this reddit thread](http://www.reddit.com/r/discworld/comments/2yt9j6/gnu_terry_pratchett/)

Installation
------------

You can install from pypi:

    pip install django-GNU-Terry-Pratchett

or from source:

    git clone git@github.com:aaronbassett/django-GNU-Terry-Pratchett.git
    cd django-GNU-Terry-Pratchett
    python setup.py install

Once installed add the middleware to you project:

    MIDDLEWARE_CLASSES=(
        ...
        'gnu_terry_pratchett.middleware.ClacksMiddleware',
    ),