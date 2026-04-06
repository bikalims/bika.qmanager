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
