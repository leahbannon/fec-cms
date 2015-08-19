FEC-CMS
+++++++

Install
=======

.. code::

    npm install
    pip install -U -r requirements.txt

Setup
=====

.. code::

    ./fec/manage.py migrate
    ./fec/manage.py createsuperuser

Local styles
------------

In `settings/local.py`:

.. code::

    FEC_STYLE_URL = 'http://localhost:8080/css/styles.css'

Run
===

.. code::
    
    ./fec/manage.py runserver