readBinary
==========

:doc:`/types/File/index`::readBinary

Reads binary data from a file.

Declaration
-----------

.. code-block:: cpp

	static std::string readBinary(const std::string& filePath);

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
	  - The path to the file to read from.

Returns
-------

The content of the file.