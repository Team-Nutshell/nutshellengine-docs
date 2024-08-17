PhysicsModuleInterface
======================

*Inherits* :doc:`/types/ModuleInterface/index` *and* :doc:`/types/SystemModuleInterface/index`.

Functions
---------

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Name
	  - Description
	* - :doc:`/types/PhysicsModuleInterface/intersect/index`
	  - Returns information about the intersection of two :doc:`ColliderShapes </types/ColliderShape/index>`.
	* - :doc:`/types/PhysicsModuleInterface/raycast/index`
	  - Casts a ray and returns information about the intersection between the ray and the :doc:`/types/ColliderShape/index`.
	* - :doc:`/types/PhysicsModuleInterface/raycastAll/index`
	  - Casts a ray and returns information about the hit :doc:`Entities </entity_component_system/entity/index>`.
	* - :doc:`/types/PhysicsModuleInterface/setConstantForces/index`
	  - Sets the constant forces.
	* - :doc:`/types/PhysicsModuleInterface/getConstantForces/index`
	  - Returns the constant forces.

.. toctree::
	:hidden:

	./intersect/index.rst
	./raycast/index.rst
	./raycastAll/index.rst
	./setConstantForces/index.rst
	./getConstantForces/index.rst