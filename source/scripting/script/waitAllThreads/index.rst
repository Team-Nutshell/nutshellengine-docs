waitAllThreads
==============

:doc:`/scripting/script/index`::waitAllThreads

Waits for all worker threads to finish their jobs.

Declaration
-----------

.. code-block:: cpp

	void waitAllThreads();

Parameters
----------

None.

Returns
-------

None.

Notes
-----

If any worker thread cannot finish its job, this function will never end.