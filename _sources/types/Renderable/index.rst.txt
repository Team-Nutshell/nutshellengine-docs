Renderable
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
	* - mesh
	  - :doc:`/types/Mesh/index`\*
	  - The memory address of the :doc:`/types/Mesh/index`.
	* - material
	  - :doc:`/types/Material/index`
	  - The :doc:`/types/Material/index` to use.

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
	* - renderable
	  - Array of Object
	  - The :doc:`/types/Renderable/index` :doc:`/entity_component_system/component/index`.
	  - .. list-table::
			:width: 100%
			:header-rows: 1
			:class: code-table

			* - Name
			  - Type
			  - Description
			  - Possible values
			* - modelPath
			  - String
			  - The path to the model.
			  - Any path to a model.
			* - primitiveIndex
			  - Number
			  - The primitive index in the model.
			  - Any number.
