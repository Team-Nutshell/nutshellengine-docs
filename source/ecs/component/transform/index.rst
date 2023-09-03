Transform
=========

Declaration
-----------

.. code-block:: cpp

	struct Transform {
		Math::vec3 position = { 0.0f, 0.0f, 0.0f };
		Math::vec3 rotation = { 0.0f, 0.0f, 0.0f };
		Math::vec3 scale = { 1.0f, 1.0f, 1.0f };
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
	  - A position.
	* - rotation
	  - Math::vec3
	  - A rotation on each axis (x, y and z). Angles are specified in radians.
	* - scale
	  - Math::vec3
	  - A scale on each axis (x, y and z).

Notes
-----

When an :doc:`/ecs/entity/index` is created, a Transform Component is automatically created and assigned to this Entity.

The Transform component defines the Entity's world position, rotation and scale.