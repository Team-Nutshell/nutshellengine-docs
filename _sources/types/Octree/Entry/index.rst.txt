Octree::Entry
=============

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - object
	  - *T*
	  - The object added to the octree.
	* - objectPosition
	  - :doc:`/types/Math/index`::vec3
	  - The center of the object's AABB added to the octree.
	* - objectSize
	  - :doc:`/types/Math/index`::vec3
	  - Half the size of the object's AABB, on each axis (x, y and z), added to the octree.