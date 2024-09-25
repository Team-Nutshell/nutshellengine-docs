SoundListener
=============

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
	  - The sound listener's forward vector.
	* - up
	  - :doc:`/types/Math/index`::vec3
	  - The sound listener's up vector.

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
	* - soundListener
	  - Array of Object
	  - The :doc:`/types/SoundListener/index` :doc:`/entity_component_system/component/index`.
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
			  - The sound listener's forward vector.
			  - Any array of 3 numbers.
			* - up
			  - Array of Number
			  - The sound listener's up vector.
			  - Any array of 3 numbers.