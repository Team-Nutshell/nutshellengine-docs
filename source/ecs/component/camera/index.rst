Camera
======

Declaration
-----------

.. code-block:: cpp

	struct Camera {
		float fov = 45.0f;
		float nearPlane = 0.3f;
		float farPlane = 200.0f;
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
	* - fov
	  - float
	  - The camera's field of view.
	* - nearPlane
	  - float
	  - The camera's near plane, which corresponds to the nearest distance from the camera's position where things are shown.
	* - farPlane
	  - float
	  - The camera's far plane, which corresponds to the furthest distance from the camera's position where things are shown.