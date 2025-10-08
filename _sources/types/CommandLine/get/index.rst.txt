get
===

:doc:`/types/CommandLine/index`::get

Returns the parsed command line.

Declaration
-----------

.. code-block:: cpp

	const std::unordered_map<std::string, std::vector<std::string>>& get();

Parameters
----------

None.

Returns
-------

The parsed command line used to launch the application.

The keys of the `std::unordered_map <https://en.cppreference.com/w/cpp/container/unordered_map>`_ are the arguments starting with "-", with the values being everything that follows.

For example:
./NutshellEngine -test1 a b -test2 c

Will return:

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Key
	  - Values
	* - ./NutshellEngine
	  - *Empty*
	* - -test1
	  - a b
	* - -test2
	  - c
