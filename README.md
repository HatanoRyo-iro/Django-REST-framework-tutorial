# Django　REST　framework　tutorial

**Awesome web-browsable Web APIs.**

Full documentation for the project is available at [https://www.django-rest-framework.org/][docs].

---

# Requirements

* Python 3.6+
* Django 4.2, 4.1, 4.0, 3.2, 3.1, 3.0

We **highly recommend** and only officially support the latest patch release of
each Python and Django series.

# Installation

Install using `pip`...

  pip install djangorestframework
  
Add `'rest_framework'` to your `INSTALLED_APPS` setting.
```python
INSTALLED_APPS = [
    ...
    'rest_framework',
]
```

# Example

Let's take a look at a quick example of using REST framework to build a simple model-backed API for accessing users and groups.

Startup up a new project like so...

    pip install django
    pip install djangorestframework
    django-admin startproject example .
    ./manage.py migrate
    ./manage.py createsuperuser

# Documentation & Support

Full documentation for the project is available at [https://www.django-rest-framework.org/][docs].

For questions and support, use the [REST framework discussion group][group], or `#restframework` on libera.chat IRC.

You may also want to [follow the author on Twitter][twitter].
