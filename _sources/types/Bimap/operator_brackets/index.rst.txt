operator[]
==========

:doc:`/types/Bimap/index`::operator[]

Returns the element according to the key passed in parameters.

Declaration
-----------

.. code-block:: cpp

	template <typename T, typename U>
	U& operator[](const T& key);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - key
	  - *T*
	  - The key of the element to return.

Returns
-------

A reference to the element associated with the key.

====

Declaration
-----------

.. code-block:: cpp

	template <typename T, typename U>
	const U operator[](const T& key) const

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - key
	  - *T*
	  - The key of the element to return.

Returns
-------

A copy of the element associated with the key.

====

Declaration
-----------

.. code-block:: cpp

	template <typename T, typename U>
	T& operator[](const U& key);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - key
	  - *U*
	  - The key of the element to return.

Returns
-------

A reference to the element associated with the key.

====

Declaration
-----------

.. code-block:: cpp

	template <typename T, typename U>
	const T operator[](const U& key) const

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - key
	  - *U*
	  - The key of the element to return.

Returns
-------

A copy of the element associated with the key.