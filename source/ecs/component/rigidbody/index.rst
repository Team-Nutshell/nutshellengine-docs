Rigidbody
=========

Declaration
-----------

.. code-block:: cpp

	struct Rigidbody {
		bool isStatic = false;
		bool isAffectedByConstants = true;
		Math::vec3 force = { 0.0f, 0.0f, 0.0f };
		float mass = 1.0f;
		float restitution = 0.0f;
		float staticFriction = 0.0f;
		float dynamicFriction = 0.0f;
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
	* - isStatic
	  - bool
	  - An :doc:`/ecs/entity/index` with a static Rigidbody is not affected by forces or collisions.
	* - isAffectedByConstants
	  - bool
	  - Specifies if the :doc:`/ecs/entity/index` is affected by the Physics Module's constants (for example: gravity).
	* - force
	  - Math::vec3
	  - The force applied on an :doc:`/ecs/entity/index` for a single frame (does not include the Physics Module's constants).
	* - mass
	  - float
	  - The mass of the :doc:`/ecs/entity/index`. **Must not be 0.0**.
	* - restitution
	  - float
	  - The coefficient of restitution, generally used for collision responses.
	* - staticFraction
	  - float
	  - The coefficient of static friction, generally used for collision responses.
	* - dynamicFraction
	  - float
	  - The coefficient of dynamic friction, generally used for collision responses.