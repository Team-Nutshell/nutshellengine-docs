Rigidbody
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
	* - isStatic
	  - bool
	  - An :doc:`/entity_component_system/entity/index` with a static Rigidbody is not affected by forces or collisions.
	* - isAffectedByConstants
	  - bool
	  - Specifies if the :doc:`/entity_component_system/entity/index` is affected by the Physics Module's constants (for example: gravity).
	* - force
	  - :doc:`/utils/Math/index`::vec3
	  - The force applied on an :doc:`/entity_component_system/entity/index` for a single frame (does not include the Physics Module's constants).
	* - mass
	  - float
	  - The mass of the :doc:`/entity_component_system/entity/index`. **Must not be 0.0**.
	* - restitution
	  - float
	  - The coefficient of restitution, generally used for collision responses.
	* - staticFraction
	  - float
	  - The coefficient of static friction, generally used for collision responses.
	* - dynamicFraction
	  - float
	  - The coefficient of dynamic friction, generally used for collision responses.