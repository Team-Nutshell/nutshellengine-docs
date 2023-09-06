operator[]
==========

:doc:`/utils/JSON/Node/index`::operator[]

Returns the element at a certain index in an Array Node or a certain key in an Object Node.

Declaration
-----------

.. code-block:: cpp

	Node& operator[](const std::string& childName);

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
	  - The name of the child.

Returns
-------

A reference to the :doc:`/utils/JSON/Node/index` associated with the key ``childName``.

Notes
-----

This function can only be called on a :doc:`/utils/JSON/Node/index` with the Object :doc:`/utils/JSON/Type/index`.

====

Declaration
-----------

.. code-block:: cpp

	const Node& operator[](const std::string& childName) const;

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
	  - The name of the child.

Returns
-------

A const reference to the :doc:`/utils/JSON/Node/index` associated with the key ``childName``.

Notes
-----

This function can only be called on a :doc:`/utils/JSON/Node/index` with the Object :doc:`/utils/JSON/Type/index`.

====

Declaration
-----------

.. code-block:: cpp

	Node& operator[](const size_t element);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - element
	  - size_t
	  - The index of the child.

Returns
-------

A reference to the :doc:`/utils/JSON/Node/index` at index ``element``.

Notes
-----

This function can only be called on a :doc:`/utils/JSON/Node/index` with the Array :doc:`/utils/JSON/Type/index`.

====

Declaration
-----------

.. code-block:: cpp

	const Node& operator[](const size_t element) const;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - element
	  - size_t
	  - The index of the child.

Returns
-------

A const reference to the :doc:`/utils/JSON/Node/index` at index ``element``.

Notes
-----

This function can only be called on a :doc:`/utils/JSON/Node/index` with the Array :doc:`/utils/JSON/Type/index`.