Transform
=========

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
	  - :doc:`/utils/Math/index`::vec3
	  - A position.
	* - rotation
	  - :doc:`/utils/Math/index`::vec3
	  - A rotation on each axis (x, y and z). Angles are specified in radians.
	* - scale
	  - :doc:`/utils/Math/index`::vec3
	  - A scale on each axis (x, y and z).

Notes
-----

When an :doc:`/entity_component_system/entity/index` is created, a Transform Component is automatically created and assigned to this Entity.

The Transform component defines the Entity's world position, rotation and scale.