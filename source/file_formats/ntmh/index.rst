.ntmh - Mesh
============

**.ntmh** is a **mesh** format, made to mimick the :doc:`/types/Mesh/index` structure. The data is **uncompressed** so it is only recommended to use it in small programs.

*.ntmh* is in the JSON format, and can be read and written using :doc:`/types/JSON/index`.

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	  - Possible values
	* - vertices
	  - Array of Object
	  - The mesh's vertices.
	  - .. list-table::
			:width: 100%
			:header-rows: 1
			:class: code-table

			* - Name
			  - Type
			  - Description
			  - Possible values
			* - position
			  - Array of Number
			  - The vertex's position.
			  - Any array of 3 numbers.
			* - normal
			  - Array of Number
			  - The vertex's normal.
			  - Any array of 3 numbers.
			* - uv
			  - Array of Number
			  - The vertex's texture coordinates.
			  - Any array of 2 numbers.
			* - color
			  - Array of Number
			  - The vertex's color.
			  - Any array of 3 numbers.
			* - tangent
			  - Array of Number
			  - The vertex's tangent.
			  - Any array of 4 numbers.
			* - joints
			  - Array of Number
			  - The vertex's bone indices.
			  - Any array of 4 numbers.
			* - weights
			  - Array of Number
			  - The vertex's bone weights.
			  - Any array of 4 numbers.
	* - indices
	  - Array of Number
	  - The mesh's indices.
	  - Any array of numbers. Size must be a multiple of 3.
	* - topology
	  - String
	  - The mesh's topology.
	  -  
		 - "TriangleList"
		 - "TriangleStrip"
		 - "LineList"
		 - "LineStrip"
		 - "PointList"
		 - "Unknown"
