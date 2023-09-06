writeBinary
===========

:doc:`/utils/File/index`::writeBinary

Writes binary data to a file.

Declaration
-----------

.. code-block:: cpp

	static void writeBinary(const std::string& filePath, const std::string& content);

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
	  - The path to the file to write to.
	* - content
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - The content to write to the file.

Returns
-------

None.