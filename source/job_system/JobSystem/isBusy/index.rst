isBusy
======

:doc:`/job_system/JobSystem/index`::isBusy

Checks if any worker thread is still executing a job.

Declaration
-----------

.. code-block:: cpp

	bool isBusy();

Parameters
----------

None.

Returns
-------

``true`` if any worker thread is still executing a job, else, returns ``false``.