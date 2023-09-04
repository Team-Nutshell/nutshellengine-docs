Bimap
=====

Utils Bimap is a bidirectional map, which means that it can both elements are a key to each other.

The main difference with the map data structure is that all elements must be unique.

Functions
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Description
	* - :doc:`/utils/Bimap/insert_or_assign/index`
	  - Inserts an element into the Bimap, according to a key. If the data already exists, its value changes.
	* - :doc:`/utils/Bimap/exist/index`
	  - Checks if an element already exists.
	* - :doc:`/utils/Bimap/erase/index`
	  - Erases an element from the map.
	* - :doc:`/utils/Bimap/operator_brackets/index`
	  - Returns the element according to the key passed in parameters.
	* - :doc:`/utils/Bimap/size/index`
	  - Returns the number of elements in the Bimap.

.. toctree::
	:hidden:

	./erase/index.rst
	./exist/index.rst
	./insert_or_assign/index.rst
	./operator_brackets/index.rst
	./size/index.rst