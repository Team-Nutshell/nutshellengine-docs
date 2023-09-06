executeJob
==========

:doc:`/scripting/script/index`::executeJob

Launches a job to be executed by a worker thread.

Declaration
-----------

.. code-block:: cpp

	void executeJob(const std::function<void()>& job);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - job
	  - const `std::function <https://en.cppreference.com/w/cpp/utility/functional/function>`_\<void()>&
	  - The job to be executed by a worker thread.

Returns
-------

None.