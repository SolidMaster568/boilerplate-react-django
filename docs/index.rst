.. django-react-boilerplate documentation master file, created by
   sphinx-quickstart on Sat Jan  4 01:36:10 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Django React Boilerplate
========================

.. image:: https://circleci.com/gh/vintasoftware/django-react-boilerplate.svg?style=svg
    :target: https://circleci.com/gh/vintasoftware/django-react-boilerplate
    :alt: Continuous integration status for Django React Boilerplate

.. image:: https://badges.greenkeeper.io/vintasoftware/django-react-boilerplate.svg
   :alt: Greenkeper status for Django React Boilerplate

A mainly `Django 2+ <https://www.djangoproject.com/>`_ project boilerplate/
template with lots of state of the art libraries, features, and tools like:

* `React 16+ <https://facebook.github.io/react/>`_, for building interactive
  UIs
* `Webpack <https://webpack.js.org/>`_, for bundling static assets
* `Celery <http://www.celeryproject.org/>`_, for background worker tasks
* `WhiteNoise <http://whitenoise.evans.io/en/stable/>`_, for efficient static files serving
* `prospector <https://prospector.readthedocs.io/en/master/>`_ and `ESLint <https://eslint.org/>`_
  with `pre-commit <https://pre-commit.com/>`_ hooks for automated quality assurance
  (doesn't replace proper testing!)
* `CircleCI <https://circleci.com/>`_, to enable continuous integration

To make this boilerplate deployable on `Heroku <https://www.heroku.com/>`_
within few steps, we've included a production-ready Django settings file and
an ``app.json`` file with the following plugins:

* `PostgreSQL <https://elements.heroku.com/addons/heroku-postgresql/>`_, for
  database provisioning
* `Redis <https://elements.heroku.com/addons/heroku-redis/>`_, for Celery
* `SendGrid <https://elements.heroku.com/addons/sendgrid/>`_, for e-mail sending
* `Papertrail <https://elements.heroku.com/addons/papertrail/>`_, for logs and
  platform errors alerts (the latter must be set manually)

To get started, check :doc:`quickstart`.

Getting started
---------------

.. toctree::
   :maxdepth: 1

   quickstart
   deployment
   contributing
   license

Commercial support
------------------

This project, as other Vinta open-source projects, is used in products of
Vinta clients. We're always looking for exciting work, so if you need any
commercial support, feel free to get in touch at contact@vinta.com.br

We're under MIT License, read :doc:`license`.
