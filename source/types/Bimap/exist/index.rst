exist
=====

:doc:`/types/Bimap/index`::exist

Declaration
-----------

.. code-block:: cpp

	template <typename T>
	bool exist(const T& key) const;

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
	  - The key to search for.

Returns
-------

``true`` if the key exists in the Bimap, else, returns ``false``.

====

Declaration
-----------

.. code-block:: cpp

	template <typename U>
	bool exist(const U& key) const;

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
	  - The key to search for.

Returns
-------

``true`` if the key exists in the Bimap, else, returns ``false``.