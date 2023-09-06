read
====

:doc:`/utils/JSON/index`::read

Reads a JSON and returns the root :doc:`/utils/JSON/Node/index`.

Declaration
-----------

.. code-block:: cpp

	static Node read(const std::string& filePath);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - filePath
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - The path to the file to read.

Returns
-------

The JSON's root :doc:`/utils/JSON/Node/index`.