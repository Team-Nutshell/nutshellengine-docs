startBlock
==========

:doc:`/types/ProfilerInterface/index`::startBlock

Starts a profiling block.

Declaration
-----------

.. code-block:: cpp

	virtual void startBlock(const std::string& blockName) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - blockName
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - The profiling block's name.

Returns
-------

None.