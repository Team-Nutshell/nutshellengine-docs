Vertex
======

Declaration
-----------

.. code-block:: cpp

	struct Vertex {
		Math::vec3 position = { 0.0f, 0.0f, 0.0f };
		Math::vec3 normal = { 0.0f, 0.0f, 0.0f };
		Math::vec2 uv = { 0.0f, 0.0f };
		Math::vec3 color = { 0.0f, 0.0f, 0.0f };
		Math::vec4 tangent = { 0.0f, 0.0f, 0.0f, 0.0f };
		Math::vec4 joints = { 0.0f, 0.0f, 0.0f, 0.0f };
		Math::vec4 weights = { 0.0f, 0.0f, 0.0f, 0.0f };
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
	* - position
	  - Math::vec3
	  - The vertex's position in **model-space**.
	* - normal
	  - Math::vec3
	  - The vertex's normal in **model-space**.
	* - uv
	  - Math::vec2
	  - The vertex's texture coordinates.
	* - color
	  - Math::vec3
	  - The vertex's color.
	* - tangent
	  - Math::vec4
	  - The vertex's tangent.
	* - joints
	  - Math::vec4
	  - The vertex's bone indices for animation.
	* - weights
	  - Math::vec4
	  - The vertex's bone weights for animation.