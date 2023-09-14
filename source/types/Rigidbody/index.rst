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
	  - Specifies if the :doc:`/entity_component_system/entity/index` is affected by the :doc:`/module/physics_module/index`'s constants (for example: gravity).
	* - force
	  - :doc:`/types/Math/index`::vec3
	  - The force applied on an :doc:`/entity_component_system/entity/index` for a single frame (does not include the :doc:`/module/physics_module/index`'s constants).
	* - mass
	  - float
	  - The mass of the :doc:`/entity_component_system/entity/index`. **Must not be 0.0**.
	* - restitution
	  - float
	  - The coefficient of restitution, generally used for collision responses.
	* - staticFriction
	  - float
	  - The coefficient of static friction, generally used for collision responses.
	* - dynamicFriction
	  - float
	  - The coefficient of dynamic friction, generally used for collision responses.

Notes
-----

JSON for the :doc:`/file_formats/ntsn/index` scene file format:

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	  - Possible values
	* - rigidbody
	  - Array of Object
	  - The :doc:`/types/Rigidbody/index` Component.
	  - .. list-table::
			:width: 100%
			:header-rows: 1
			:class: code-table

			* - Name
			  - Type
			  - Description
			  - Possible values
			* - isStatic
			  - bool
			  - An :doc:`/entity_component_system/entity/index` with a static Rigidbody is not affected by forces or collisions.
			  - Any boolean (``true`` or ``false``).
			* - isAffectedByConstants
			  - bool
			  - Specifies if the :doc:`/entity_component_system/entity/index` is affected by the Physics Module's constants (for example: gravity).
			  - Any boolean (``true`` or ``false``).
			* - mass
			  - Number
			  - The mass of the :doc:`/entity_component_system/entity/index`. **Must not be 0.0**.
			  - Any number excepted 0.0.
			* - restitution
			  - Number
			  - The coefficient of restitution, generally used for collision responses.
			  - Any number.
			* - staticFriction
			  - Number
			  - The coefficient of static friction, generally used for collision responses.
			  - Any number.
			* - dynamicFriction
			  - Number
			  - The coefficient of dynamic friction, generally used for collision responses.
			  - Any number.