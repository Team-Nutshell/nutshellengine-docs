JobSystem
=========

*Inherits* :doc:`/types/JobSystemInterface/index`.

Functions
---------

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Name
	  - Description
	* - :doc:`/types/JobSystem/execute/index`
	  - Launches a job to be executed by a worker thread.
	* - :doc:`/types/JobSystem/dispatch/index`
	  - Launches a job to be executed by multiple worker threads.
	* - :doc:`/types/JobSystem/isBusy/index`
	  - Checks if any worker thread is still executing a job.
	* - :doc:`/types/JobSystem/wait/index`
	  - Waits for all worker threads to finish their jobs.
	* - :doc:`/types/JobSystem/getNumThreads/index`
	  - Returns the number of threads.

.. toctree::
	:hidden:

	./execute/index.rst
	./dispatch/index.rst
	./isBusy/index.rst
	./wait/index.rst
	./getNumThreads/index.rst