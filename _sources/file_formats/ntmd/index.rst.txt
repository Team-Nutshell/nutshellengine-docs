.ntmd - Model
=============

**.ntmd** is a **model** format, like *.gltf*, but made to mimick the :doc:`/types/Model/index` structure.

*.ntmd* is in the JSON format, and can be read and written using :doc:`/types/JSON/index`.

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	  - Possible values
	* - primitives
	  - Array of Object
	  - The model's primitives.
	  - .. list-table::
			:width: 100%
			:header-rows: 1
			:class: code-table

			* - Name
			  - Type
			  - Description
			  - Possible values
			* - meshPath
			  - String
			  - The path to the :doc:`/file_formats/ntmh/index`.
			  - A path to a mesh.
			* - materialPath
			  - String
			  - The path to the :doc:`/file_formats/ntml/index`.
			  - A path to a material.