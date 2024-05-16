start
=====

:doc:`/types/ProfilerInterface/index`::start

Starts a profiling session.

Declaration
-----------

.. code-block:: cpp

	virtual void start(const std::string& sessionName) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - sessionName
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - The profiling session's name.

Returns
-------

None.