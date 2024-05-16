to_string
=========

:doc:`/types/ProfilerResultNode/index`::to_string

Converts the profiler results to a string.

Declaration
-----------

.. code-block:: cpp

	static std::string to_string(const ProfilerResultNode& resultNode);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - resultNode
	  - const :doc:`/types/ProfilerResultNode/index`\&
	  - The root :doc:`/types/ProfilerResultNode/index`.

Returns
-------

The profiler results as a string for the whole hierarchy, with ``resultNode`` as root.