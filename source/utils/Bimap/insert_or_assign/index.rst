insert_or_assign
================

:doc:`/utils/Bimap/index`::insert_or_assign

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
	  - The element to add to the :doc:`/utils/Bimap/index`.

Returns
-------

None.

Notes
-----

The ``key`` is assigned to an ``element``, but as the :doc:`/utils/Bimap/index` is bidirectional, the ``element`` is also the key for the ``key``.

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
	  - The element to add to the :doc:`/utils/Bimap/index`.

Returns
-------

None.

Notes
-----

The ``key`` is assigned to an ``element``, but as the :doc:`/utils/Bimap/index` is bidirectional, the ``element`` is also the key for the ``key``.