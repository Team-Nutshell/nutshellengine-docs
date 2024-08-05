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
	  - The :doc:`/types/Collidable/index` :doc:`/entity_component_system/component/index`.
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
				 - "Box"
				 - "Sphere"
				 - "Capsule"
			* - center
			  - Array of Number
			  - The sphere or box's center, in **object-space**. (if ``type`` is "Box" or "Sphere").
			  - Any array of 3 numbers.
			* - radius
			  - Number
			  - The sphere or capsule's radius. (if ``type`` is "Sphere" or "Capsule").
			  - Any number.
			* - halfExtent
			  - Array of Number
			  - The OBB's half size. (if ``type`` is "Box").
			  - Any array of 3 numbers.
			* - rotation
			  - Array of Number
			  - The OBB's rotation on each axis, in **degrees**. (if ``type`` is "Box").
			  - Any array of 3 numbers.
			* - base
			  - Array of Number
			  - The capsule's base, in **object-space**. (if ``type`` is "Capsule").
			  - Any array of 3 numbers.
			* - tip
			  - Array of Number
			  - The capsule's tip, in **object-space**. (if ``type`` is "Capsule").
			  - Any array of 3 numbers.

If the only information specified in the scene file is the :doc:`/types/Collidable/index`'s type, the shape will be defined with default values, which are:

* "Box": A box with an half extent of 0.5 on each axis, which gives it a size of 1.
* "Sphere": A sphere with a radius of 0.5, which gives it a diameter of 1.
* "Capsule": A capsule with a segment length of 0.5 and a radius of 0.25.
