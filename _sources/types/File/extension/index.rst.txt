extension
=========

:doc:`/types/File/index`::extension

Returns the file's extension.

Declaration
-----------

.. code-block:: cpp

	static std::string extension(const std::string& filePath);

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
	  - The path to the file to get the extension of.

Returns
-------

The file's extension, without the ".".