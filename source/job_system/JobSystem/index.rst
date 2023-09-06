JobSystem
=========

Functions
---------

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Name
	  - Description
	* - :doc:`/job_system/JobSystem/execute/index`
	  - Launches a job to be executed by a worker thread.
	* - :doc:`/job_system/JobSystem/dispatch/index`
	  - Launches a job to be executed by multiple worker threads.
	* - :doc:`/job_system/JobSystem/isBusy/index`
	  - Checks if any worker thread is still executing a job.
	* - :doc:`/job_system/JobSystem/wait/index`
	  - Waits for all worker threads to finish their jobs.
	* - :doc:`/job_system/JobSystem/getNumThreads/index`
	  - Returns the number of threads.

.. toctree::
	:hidden:

	./execute/index.rst
	./dispatch/index.rst
	./isBusy/index.rst
	./wait/index.rst
	./getNumThreads/index.rst