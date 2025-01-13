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
	* - projectionType
	  - :doc:`/types/CameraProjectionType/index`
	  - The camera's projection type.
	* - fov
	  - float
	  - The camera's field of view. Only used by perspective projection cameras. In radians.
	* - left
	  - float
	  - The camera's left border. Only used by orthographic projection cameras.
	* - right
	  - float
	  - The camera's right border. Only used by orthographic projection cameras.
	* - bottom
	  - float
	  - The camera's bottom border. Only used by orthographic projection cameras.
	* - top
	  - float
	  - The camera's top border. Only used by orthographic projection cameras.
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
			* - projectionType
			  - The :doc:`/types/CameraProjectionType/index`.
			  - 
				 - "Perspective"
				 - "Orthographic"
			* - fov
			  - Number
			  - The camera's field of view. Only used by perspective projection cameras. In degrees.
			  - Any number.
			* - left
			  - float
			  - The camera's left border. Only used by orthographic projection cameras.
			  - Any number.
			* - right
			  - float
			  - The camera's right border. Only used by orthographic projection cameras.
			  - Any number.
			* - bottom
			  - float
			  - The camera's bottom border. Only used by orthographic projection cameras.
			  - Any number.
			* - top
			  - float
			  - The camera's top border. Only used by orthographic projection cameras.
			  - Any number.
			* - nearPlane
			  - Number
			  - The camera's near plane.
			  - Any number.
			* - farPlane
			  - Number
			  - The camera's far plane.
			  - Any number.