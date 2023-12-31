readAscii
=========

:doc:`/types/File/index`::readAscii

Reads ASCII data from a file.

Declaration
-----------

.. code-block:: cpp

	static std::string readAscii(const std::string& filePath);

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