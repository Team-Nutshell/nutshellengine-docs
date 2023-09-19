Collidable
==========

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
	  - `std::unique_ptr <https://en.cppreference.com/w/cpp/memory/unique_ptr>`_\<:doc:`/types/ColliderShape/index`>
	  - The collider's properties.

Notes
-----

The Collidable contains a :doc:`/types/ColliderShape/index` structure, which defines its :doc:`/types/ColliderShapeType/index` and properties.

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
	  - The :doc:`/types/Collidable/index` Component.
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
			  -  
				 - "Sphere"
				 - "AABB"
				 - "OBB"
				 - "Capsule"
			* - center
			  - Array of Number
			  - The sphere or OBB's center, in **object-space**. (if ``type`` is "Sphere" or "OBB").
			  - Any array of 3 numbers.
			* - radius
			  - Number
			  - The sphere or capsule's radius. (if ``type`` is "Sphere" or "Capsule").
			  - Any number.
			* - min
			  - Array of Number
			  - The AABB's minimum corner, in **object-space**. (if ``type`` is "AABB").
			  - Any array of 3 numbers.
			* - max
			  - Array of Number
			  - The AABB's maximum corner, in **object-space**. (if ``type`` is "AABB").
			  - Any array of 3 numbers.
			* - halfExtent
			  - Array of Number
			  - The OBB's half size. (if ``type`` is "OBB").
			  - Any array of 3 numbers.
			* - rotation
			  - Array of Number
			  - The OBB's rotation on each axis, in **degrees**. (if ``type`` is "OBB").
			  - Any array of 3 numbers.
			* - base
			  - Array of Number
			  - The capsule's base, in **object-space**. (if ``type`` is "Capsule").
			  - Any array of 3 numbers.
			* - tip
			  - Array of Number
			  - The capsule's tip, in **object-space**. (if ``type`` is "Capsule").
			  - Any array of 3 numbers.
