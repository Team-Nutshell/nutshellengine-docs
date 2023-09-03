AABBCollidable
==============

Declaration
-----------

.. code-block:: cpp

	struct AABBCollidable {
		ColliderAABB collider;
	};

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - collider
	  - :doc:`/types/collider_aabb/index`
	  - The collider's properties.

Notes
-----

The AABBCollidable contains a :doc:`/types/collider_aabb/index` structure, which defines its boundaries.