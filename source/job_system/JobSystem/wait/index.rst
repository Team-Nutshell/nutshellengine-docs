wait
====

:doc:`/job_system/JobSystem/index`::wait

Waits for all worker threads to finish their jobs.

Declaration
-----------

.. code-block:: cpp

	void wait();

Parameters
----------

None.

Returns
-------

None.

Notes
-----

If any worker thread cannot finish its job, this function will never end.