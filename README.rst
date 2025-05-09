.. This README is meant for consumption by humans and pypi. Pypi can render rst files so please do not use Sphinx features.
   If you want to learn more about writing documentation, please check out: http://docs.plone.org/about/documentation_styleguide.html
   This text does not appear on pypi or github. It is a comment.

.. image:: https://travis-ci.org/collective/bika.qmanager.svg?branch=master
    :target: https://travis-ci.org/collective/bika.qmanager

.. image:: https://coveralls.io/repos/github/collective/bika.qmanager/badge.svg?branch=master
    :target: https://coveralls.io/github/collective/bika.qmanager?branch=master
    :alt: Coveralls

.. image:: https://img.shields.io/pypi/v/bika.qmanager.svg
    :target: https://pypi.python.org/pypi/bika.qmanager/
    :alt: Latest Version

.. image:: https://img.shields.io/pypi/status/bika.qmanager.svg
    :target: https://pypi.python.org/pypi/bika.qmanager
    :alt: Egg Status

.. image:: https://img.shields.io/pypi/pyversions/bika.qmanager.svg?style=plastic   :alt: Supported - Python Versions

.. image:: https://img.shields.io/pypi/l/bika.qmanager.svg
    :target: https://pypi.python.org/pypi/bika.qmanager/
    :alt: License


=============
bika.qmanager
=============

bika.qmanager extends the functionality of `senaite.queue <https://github.com/senaite/senaite.queue>`_. To set it up, follow the documentation provided on the senaite.queue `docs site <https://github.com/senaite/senaite.queue>`_.

Required Components
-------------------
1) ``queue_server``

   Responsible for queuing tasks.

2) ``queue_consumer``

   Executes the queued tasks. This can be triggered by: 
           - A cron job
           - Direct access to the URL: /senaite/queue_consume


Contribute
----------

- Issue Tracker: https://github.com/bikalims/bika.qmanager/issues
- Source Code: https://github.com/bikalims/bika.qmanager


License
-------

The project is licensed under the GPLv2.
