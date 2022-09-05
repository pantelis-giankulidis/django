# Quick install guide

Before you can use Django, you'll need to get it installed. We have a
[complete installation guide](../topics/install.txt) that covers all the
possibilities; this guide will guide you to a minimal installation that'll work
while you walk through the introduction.

## Install Python

Being a Python web framework, Django requires Python. See
`faq-python-version-support` for details. Python includes a lightweight
database called [SQLite](https://www.sqlite.org/) so you won't need to set up a database just yet.


Get the latest version of Python [by clicking here](https://www.python.org/downloads/), or with
your operating system's package manager.

You can verify that Python is installed by typing ``python`` from your shell;
you should see something like::

    Python 3.x.y
    [GCC 4.x] on linux
    Type "help", "copyright", "credits" or "license" for more information.
    >>>

## Set up a database

This step is only necessary if you'd like to work with a "large" database engine
like PostgreSQL, MariaDB, MySQL, or Oracle. To install such a database, consult
the `database installation information`.

## Install Django

You've got three options to install Django:

* Install an official release. This
  is the best approach for most users.

* Install a version of Django provided by your operating system
  distribution.

* Install the latest development version. This option is for enthusiasts who want
  the latest-and-greatest features and aren't afraid of running brand new code.
  You might encounter new bugs in the development version, but reporting them
  helps the development of Django. Also, releases of third-party packages are
  less likely to be compatible with the development version than with the
  latest stable release.



    If you do either of the first two steps, keep an eye out for parts of the
    documentation marked **new in development version**. That phrase flags
    features that are only available in development versions of Django, and
    they likely won't work with an official release.


## Verifying

To verify that Django can be seen by Python, type ``python`` from your shell.
Then at the Python prompt, try to import Django:


    >>> import django
    >>> print(django.get_version())
    |version|

You may have another version of Django installed.

## That's it!

That's it -- you can now [move onto the tutorial](../intro/tutorial01.md)
