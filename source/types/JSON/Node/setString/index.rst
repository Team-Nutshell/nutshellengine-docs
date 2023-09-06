setString
=========

:doc:`/types/JSON/Node/index`::setString

Sets the value of a String Node.

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
	  - The value to set for the :doc:`/types/JSON/Node/index`.

Returns
-------

None.

Notes
-----

This function can only be called on a :doc:`/types/JSON/Node/index` with the String :doc:`/types/JSON/Type/index`.