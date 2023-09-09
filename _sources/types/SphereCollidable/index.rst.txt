SphereCollidable
================

Declaration
-----------

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
	  - :doc:`/types/ColliderSphere/index`
	  - The collider's properties.

Notes
-----

The SphereCollidable contains a :doc:`/types/ColliderSphere/index` structure, which defines its properties.

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
	  - The :doc:`/types/SphereCollidable/index` Component.
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
			  - "Sphere"
			* - center
			  - Array of Number
			  - The sphere's center, in **object-space**.
			  - Any array of 3 numbers.
			* - radius
			  - Number
			  - The sphere's radius.
			  - Any number.