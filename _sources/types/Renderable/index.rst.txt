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
	* - model
	  - :doc:`/types/Model/index`\*
	  - The memory address of the :doc:`/types/Model/index`.
	* - modelPrimitiveIndex
	  - uint32_t
	  - The index of the :doc:`/types/ModelPrimitive/index` in ``model``.

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

If the :doc:`/types/Model/index` loaded in ``modelPath`` contains multiple :doc:`ModelPrimitives </types/ModelPrimitive/index>`, an :doc:`/entity_component_system/entity/index` will be created for each :doc:`/types/ModelPrimitive/index`. If a name for the base Entity was specified, the index of the :doc:`/types/ModelPrimitive/index` in the :doc:`/types/Model/index` will be appended at the end of the name, preceded by a "_", for each created :doc:`/entity_component_system/entity/index`, even if the :doc:`/types/Model/index` only contained a single :doc:`/types/ModelPrimitive/index`.