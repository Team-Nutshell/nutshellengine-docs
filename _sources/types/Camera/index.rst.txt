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
	* - fov
	  - float
	  - The camera's field of view.
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
	  - The :doc:`/types/Camera/index` Component.
	  - .. list-table::
			:width: 100%
			:header-rows: 1
			:class: code-table

			* - Name
			  - Type
			  - Description
			  - Possible values
			* - fov
			  - Number
			  - The camera's field of view, in degrees.
			  - Any number.
			* - nearPlane
			  - Number
			  - The camera's near plane.
			  - Any number.
			* - farPlane
			  - Number
			  - The camera's far plane.
			  - Any number.