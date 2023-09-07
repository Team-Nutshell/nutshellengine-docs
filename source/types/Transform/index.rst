Transform
=========

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - position
	  - :doc:`/types/Math/index`::vec3
	  - A position.
	* - rotation
	  - :doc:`/types/Math/index`::vec3
	  - A rotation on each axis (x, y and z). Angles are specified in radians.
	* - scale
	  - :doc:`/types/Math/index`::vec3
	  - A scale on each axis (x, y and z).

Notes
-----

When an :doc:`/entity_component_system/entity/index` is created, a Transform Component is automatically created and assigned to this Entity.

The Transform component defines the Entity's world position, rotation and scale.

JSON for the :doc:`/file_formats/ntsn/index` scene file format:

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	  - Possible values
	* - transform
	  - Array of Object
	  - The :doc:`/types/Transform/index` Component.
	  - .. list-table::
			:width: 100%
			:header-rows: 1
			:class: code-table

			* - Name
			  - Type
			  - Description
			  - Possible values
			* - position
			  - Array of Number
			  - A position.
			  - Any array of 3 numbers.
			* - rotation
			  - Array of Number
			  - A rotation on each axis (x, y and z). Angles are specified in radians.
			  - Any array of 3 numbers.
			* - scale
			  - Array of Number
			  - A scale on each axis (x, y and z).
			  - Any array of 3 numbers.