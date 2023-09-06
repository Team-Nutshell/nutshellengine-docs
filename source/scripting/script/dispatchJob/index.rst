dispatchJob
===========

:doc:`/scripting/script/index`::dispatchJob

Launches a job to be executed by multiple worker threads.

Declaration
-----------

.. code-block:: cpp

	void dispatchJob(uint32_t jobCount, uint32_t jobsPerWorker, const std::function<void(JobDispatchArguments)>& job);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - jobCount
	  - uint32_t
	  - The total number of jobs to execute.
	* - jobsPerWorker
	  - uint32_t
	  - The number of jobs each worker will execute.
	* - job
	  - const `std::function <https://en.cppreference.com/w/cpp/utility/functional/function>`_\<void(:doc:`/job_system/JobDispatchArguments/index`)>&
	  - The job to be executed by the worker threads.

Returns
-------

None.