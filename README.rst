=====================
 ProyectoCiencia.org
=====================

Dependencias
============

Pip y Virtualenv (Preferiblemente Virtualenvwrapper).

En un virtualenv, instale Mezzanine:

::

    $ pip install -U mezzanine


Para probar en un servidor de desarrollo::

    $ python manage.py createdb --noinput
    $ python manage.py runserver

La clave/pwd del admin por defecto es admin/default
