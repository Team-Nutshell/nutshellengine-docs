AABBCollidable
==============

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
	  - :doc:`/types/ColliderAABB/index`
	  - The collider's properties.

Notes
-----

The AABBCollidable contains a :doc:`/types/ColliderAABB/index` structure, which defines its boundaries.

JSON for the :doc:`/file_formats/ntsn/index` scene file format:

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	  - Possible values
	* - collidable
	  - Array of Object
	  - The :doc:`/types/AABBCollidable/index` Component.
	  - .. list-table::
			:width: 100%
			:header-rows: 1
			:class: code-table

			* - Name
			  - Type
			  - Description
			  - Possible values
			* - type
			  - String
			  - The :doc:`/types/ColliderShapeType/index`.
			  - "AABB"
			* - min
			  - Array of Number
			  - The AABB's minimum corner, in **object-space**.
			  - Any array of 3 numbers.
			* - max
			  - Array of Number
			  - The AABB's maximum corner, in **object-space**.
			  - Any array of 3 numbers.
