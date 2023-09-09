RaycastInformation
==================

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - entity
	  - :doc:`/entity_component_system/entity/index`
	  - The hit :doc:`/entity_component_system/entity/index`.
	* - distance
	  - float
	  - The closest distance to the hit :doc:`/entity_component_system/entity/index`.
	* - normal
	  - :doc:`/types/Math/index`::vec3
	  - The normal of the hit surface.

Notes
-----

RaycastInformation is returned by the :doc:`/scripting/api/index`'s :doc:`/types/Script/raycast/index` function or the :doc:`/module/physics_module/index`'s :doc:`/types/PhysicsModuleInterface/raycast/index` function.

To find the position of the intersection, knowing ``rayOrigin`` the origin position of the ray in world-space and ``rayDirection`` the direction of the ray:

:math:`intersectionPosition = rayOrigin + (rayDirection * distance)`