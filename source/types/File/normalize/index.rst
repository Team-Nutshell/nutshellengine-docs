normalize
=========

:doc:`/types/File/index`::normalize

Returns the normalized form of a path.

Declaration
-----------

.. code-block:: cpp

	static std::string normalize(const std::string& filePath);

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
	  - The path to get the normalized form of.

Returns
-------

The normalized form of a path. For example:
- ``/a/b/../c/d/.././e.ntsn`` gives ``/a/c/e.ntsn``.
- ``C:\\a\\b.ntsn`` gives ``C:/a/b.ntsn``.
- ``C:\\Application\\assets\\scenes\\test.ntsn`` with ``Application`` being the project directory gives ``assets/scenes/test.ntsn``.