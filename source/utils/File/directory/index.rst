directory
=========

:doc:`/utils/File/index`::directory

Declaration
-----------

.. code-block:: cpp

	static std::string directory(const std::string& filePath);

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
	  - The path to the file to get the directory of.

Returns
-------

The file's directory, without the filename.