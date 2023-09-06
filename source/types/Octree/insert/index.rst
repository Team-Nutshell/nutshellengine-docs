insert
======

:doc:`/types/Octree/index`::insert

Inserts an element in the Octree.

Declaration
-----------

.. code-block:: cpp

	template <typename T>
	void insert(T object, const Math::vec3& objectPosition, const Math::vec3& objectSize);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - object
	  - *T*
	  - The object to add to the octree.
	* - objectPosition
	  - :doc:`/types/Math/index`::vec3
	  - The center of the object's AABB to add to the octree.
	* - objectSize
	  - :doc:`/types/Math/index`::vec3
	  - Half the size of the object's AABB, on each axis (x, y and z), to add to the octree.

Returns
-------

None.