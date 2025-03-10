Light
=====

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - type
	  - :doc:`/types/LightType/index`
	  - The light's type.
	* - color
	  - :doc:`/types/Math/index`::vec3
	  - The light's color.
	* - intensity
	  - float
	  - The light's intensity, it is multiplied with the color.
	* - direction
	  - :doc:`/types/Math/index`::vec3
	  - The light's base direction vector.
	* - cutoff
	  - :doc:`/types/Math/index`::vec2
	  - The light's cutoff values. Only used by spot lights. In radians.

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
	* - light
	  - Array of Object
	  - The :doc:`/types/Light/index` :doc:`/entity_component_system/component/index`.
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
			  - The :doc:`/types/LightType/index`.
			  - 
				 - "Directional"
				 - "Point"
				 - "Spot"
				 - "Ambient"
			* - color
			  - Array of Number
			  - The light's color.
			  - Any array of 3 numbers.
			* - intensity
			  - Number
			  - The light's intensity.
			  - Any number.
			* - direction
			  - Array of Number
			  - The light's base direction vector.
			  - Any array of 3 numbers.
			* - cutoff
			  - Array of Number
			  - Only used by spot lights. In degrees.
			  - Any array of 2 numbers.