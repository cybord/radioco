#######
RadioCo
#######

RadioCo is a broadcasting radio recording scheduling system. RadioCo has been
intended to provide a solution for a wide range of broadcast projects, from
community to public and commercial stations.

********
Features
********

* designed to work with any web browser
* drag and drop scheduling calendar interface
* live shows can be recorded and published automatically
* complete authentication system (user accounts, groups, permissions)

* ...and much more

More information on `our website <http://radioco.org/>`_.

*************
Documentation
*************

Please head over to our `documentation <http://django-radio.readthedocs.org/>`_ for all
the details on how to install, extend and use RadioCo.

***********
Quick Start
***********

You can use a `configured radioco project  <https://github.com/iago1460/radioco>`_::

    sudo apt-get install git-core python-dev python-pip python-virtualenv
    git clone https://github.com/iago1460/radioco
    cd radioco
    virtualenv .
    source bin/activate
    pip install -r requirements.txt
    python manage.py migrate
    python manage.py runserver

That should be it. Point a web browser to `127.0.0.1:8000 <http://127.0.0.1:8000>`_ : you
should get the RadioCo Index screen.
