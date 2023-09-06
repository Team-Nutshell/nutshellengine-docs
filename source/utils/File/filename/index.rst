filename
========

:doc:`/utils/File/index`::filename

Returns the filename without the extension.

Declaration
-----------

.. code-block:: cpp

	static std::string filename(const std::string& filePath);

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
	  - The path to the file to get the filename of.

Returns
-------

The filename of the file, without the extension.