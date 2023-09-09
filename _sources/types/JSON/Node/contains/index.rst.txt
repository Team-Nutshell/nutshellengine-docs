contains
========

:doc:`/types/JSON/Node/index`::contains

Checks if the Object Node contains a certain key.

Declaration
-----------

.. code-block:: cpp

	bool contains(const std::string& childName) const;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - childName
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - The name of the child to check the existence of.

Returns
-------

``true`` if the Object :doc:`/types/JSON/Node/index` contains a child with the name ``childName``, else, returns ``false``.

Notes
-----

This function can only be called on a :doc:`/types/JSON/Node/index` with the Object :doc:`/types/JSON/Type/index`.