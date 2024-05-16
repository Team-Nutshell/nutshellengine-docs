ProfilerResultNode
==================

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - name
	  - `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_
	  - The block's name.
	* - times
	  - `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_\<double>
	  - The block's times of execution, in milliseconds.
	* - totalTime
	  - double
	  - The block's total execution time, in milliseconds.
	* - meanTime
	  - double
	  - The block's mean execution time, in milliseconds.
	* - minTimeIndex
	  - uint32_t
	  - The index of the lowest execution time in ``times``.
	* - minTime
	  - double
	  - The block's lowest execution time, in milliseconds.
	* - maxTimeIndex
	  - uint32_t
	  - The index of the highest execution time in ``times``.
	* - maxTime
	  - double
	  - The block's highest execution time, in milliseconds.
	* - children
	  - `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_\<:doc:`/types/ProfilerResultNode/index`>
	  - The block's children.

Static Functions
----------------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Description
	* - :doc:`/types/ProfilerResultNode/to_string/index`
	  - Converts the profiler results to a string.

.. toctree::
	:hidden:

	./to_string/index.rst