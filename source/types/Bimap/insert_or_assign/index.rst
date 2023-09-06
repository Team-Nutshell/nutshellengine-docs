insert_or_assign
================

:doc:`/types/Bimap/index`::insert_or_assign

Inserts an element into the Bimap, according to a key. If the data already exists, its value changes.

Declaration
-----------

.. code-block:: cpp

	template <typename T, typename U>
	void insert_or_assign(const T& key, const U& elem);

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
	  - The key of the element to add.
	* - elem
	  - *U*
	  - The element to add to the :doc:`/types/Bimap/index`.

Returns
-------

None.

Notes
-----

The ``key`` is assigned to an ``element``, but as the :doc:`/types/Bimap/index` is bidirectional, the ``element`` is also the key for the ``key``.

====

Declaration
-----------

.. code-block:: cpp

	template <typename T, typename U>
	void insert_or_assign(const TU& key, const T& elem);

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
	  - The key of the element to add.
	* - elem
	  - *T*
	  - The element to add to the :doc:`/types/Bimap/index`.

Returns
-------

None.

Notes
-----

The ``key`` is assigned to an ``element``, but as the :doc:`/types/Bimap/index` is bidirectional, the ``element`` is also the key for the ``key``.