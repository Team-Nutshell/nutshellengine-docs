addObject
=========

:doc:`/types/JSON/Node/index`::addObject

Adds an element to an Array Node or to certain key in an Object Node.

Declaration
-----------

.. code-block:: cpp

	void addObject(const std::string& childName, Node* childNode);

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
	  - The name of the child to add to the :doc:`/types/JSON/Node/index`.
	* - childNode
	  - :doc:`/types/JSON/Node/index`\*
	  - The memory address of the :doc:`/types/JSON/Node/index` to add as a child.

Returns
-------

None.

Notes
-----

This function can only be called on a :doc:`/types/JSON/Node/index` with the Object :doc:`/types/JSON/Type/index`.

====

Declaration
-----------

.. code-block:: cpp

	void addObject(Node* element);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - childNode
	  - :doc:`/types/JSON/Node/index`\*
	  - The memory address of the :doc:`/types/JSON/Node/index` to add as a child.

Returns
-------

None.

Notes
-----

This function can only be called on a :doc:`/types/JSON/Node/index` with the Array :doc:`/types/JSON/Type/index`.

``childNode`` is added at the end of the list.