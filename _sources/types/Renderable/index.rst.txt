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
	* - fragmentShader
	  - `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_
	  - The custom `/fragment_shader/index` to use. If empty, the graphics module's default fragment shader will be used.
	* - isVisible
	  - bool
	  - Specifies if the :doc:`/entity_component_system/entity/index` is visible.
	* - castsShadows
	  - bool
	  - Specifies if the :doc:`/entity_component_system/entity/index` casts shadows.

Notes
-----

The :doc:`/entity_component_system/entity/index` will still cast shadows if ``castsShadows`` is ``true`` and ``isVisible`` is ``false``.

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
			* - materialPath
			  - String
			  - The path to the material.
			  - Any path to a material.
			* - fragmentShaderPath
			  - String
			  - The path to the fragment shader.
			  - Any path to a fragment shader.
			* - isVisible
			  - Boolean
			  - Specifies if the :doc:`/entity_component_system/entity/index` is visible.
			  - Any boolean (``true`` or ``false``).
			* - castsShadows
			  - Boolean
			  - Specifies if the :doc:`/entity_component_system/entity/index` casts shadows.
			  - Any boolean (``true`` or ``false``).
