Vertex
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
	* - position
	  - :doc:`/types/Math/index`::vec3
	  - The vertex's position in **model-space**.
	* - normal
	  - :doc:`/types/Math/index`::vec3
	  - The vertex's normal in **model-space**.
	* - uv
	  - :doc:`/types/Math/index`::vec2
	  - The vertex's texture coordinates.
	* - color
	  - :doc:`/types/Math/index`::vec3
	  - The vertex's color.
	* - tangent
	  - :doc:`/types/Math/index`::vec4
	  - The vertex's tangent.
	* - joints
	  - `std::array <https://en.cppreference.com/w/cpp/container/array>`_\<uint32_t, 4>
	  - The vertex's bone indices for animation.
	* - weights
	  - :doc:`/types/Math/index`::vec4
	  - The vertex's bone weights for animation.