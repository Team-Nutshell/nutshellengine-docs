setString
=========

:doc:`/utils/JSON/Node/index`::setString

Declaration
-----------

.. code-block:: cpp

	void setString(const std::string& string);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - string
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - The value to set for the :doc:`/utils/JSON/Node/index`.

Returns
-------

None.

Notes
-----

This function can only be called on a :doc:`/utils/JSON/Node/index` with the String :doc:`/utils/JSON/Type/index`.