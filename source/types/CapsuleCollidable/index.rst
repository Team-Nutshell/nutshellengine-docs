CapsuleCollidable
=================

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
	  - :doc:`/types/ColliderCapsule/index`
	  - The collider's properties.

Notes
-----

The CapsuleCollidable contains a :doc:`/types/ColliderCapsule/index` structure, which defines its properties.

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
	  - The :doc:`/types/CapsuleCollidable/index` Component.
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
			  - "Capsule"
			* - base
			  - Array of Number
			  - The capsule's base, in **object-space**.
			  - Any array of 3 numbers.
			* - tip
			  - Array of Number
			  - The capsule's tip, in **object-space**.
			  - Any array of 3 numbers.
			* - radius
			  - Number
			  - The capsule's radius.
			  - Any number.