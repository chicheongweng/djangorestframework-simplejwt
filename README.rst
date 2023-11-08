Simple JWT
==========

.. image:: https://jazzband.co/static/img/badge.svg
   :target: https://jazzband.co/
   :alt: Jazzband
.. image:: https://github.com/jazzband/djangorestframework-simplejwt/workflows/Test/badge.svg
   :target: https://github.com/jazzband/djangorestframework-simplejwt/actions
   :alt: GitHub Actions
.. image:: https://codecov.io/gh/jazzband/djangorestframework-simplejwt/branch/master/graph/badge.svg
  :target: https://codecov.io/gh/jazzband/djangorestframework-simplejwt
.. image:: https://img.shields.io/pypi/v/djangorestframework-simplejwt.svg
  :target: https://pypi.python.org/pypi/djangorestframework-simplejwt
.. image:: https://img.shields.io/pypi/pyversions/djangorestframework-simplejwt.svg
  :target: https://pypi.python.org/pypi/djangorestframework-simplejwt
.. image:: https://img.shields.io/pypi/djversions/djangorestframework-simplejwt.svg
  :target: https://pypi.python.org/pypi/djangorestframework-simplejwt
.. image:: https://readthedocs.org/projects/django-rest-framework-simplejwt/badge/?version=latest
  :target: https://django-rest-framework-simplejwt.readthedocs.io/en/latest/

Abstract
--------

Simple JWT is a JSON Web Token authentication plugin for the `Django REST
Framework <http://www.django-rest-framework.org/>`__.

For full documentation, visit `django-rest-framework-simplejwt.readthedocs.io
<https://django-rest-framework-simplejwt.readthedocs.io/en/latest/>`__.


Translations
------------

Contribute translations directly with PRs or via inlang https://inlang.com/editor/github.com/jazzband/djangorestframework-simplejwt


Installation and Test
---------------------

cd [project directory]

mkvirtualenv simplejwt

workon simplejwt

pip install --upgrade pip

pip install .

pip install -e .[test,doc,lint,dev,python-jose,crypto]

pip install pytest

pytest tests

pytest -s tests (don't suppress printouts in test cases)
