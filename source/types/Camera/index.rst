Camera
======

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - forward
	  - :doc:`/types/Math/index`::vec3
	  - The camera's forward vector.
	* - up
	  - :doc:`/types/Math/index`::vec3
	  - The camera's up vector.
	* - fov
	  - float
	  - The camera's field of view. In radians.
	* - nearPlane
	  - float
	  - The camera's near plane, which corresponds to the nearest distance from the camera's position where things are shown.
	* - farPlane
	  - float
	  - The camera's far plane, which corresponds to the furthest distance from the camera's position where things are shown.

Notes
-----

JSON for the :doc:`/file_formats/ntsn/index` scene file format:

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	  - Possible values
	* - camera
	  - Array of Object
	  - The :doc:`/types/Camera/index` :doc:`/entity_component_system/component/index`.
	  - .. list-table::
			:width: 100%
			:header-rows: 1
			:class: code-table

			* - Name
			  - Type
			  - Description
			  - Possible values
			* - forward
			  - Array of Number
			  - The camera's forward vector.
			  - Any array of 3 numbers.
			* - up
			  - Array of Number
			  - The camera's up vector.
			  - Any array of 3 numbers.
			* - fov
			  - Number
			  - The camera's field of view. In degrees.
			  - Any number.
			* - nearPlane
			  - Number
			  - The camera's near plane.
			  - Any number.
			* - farPlane
			  - Number
			  - The camera's far plane.
			  - Any number.