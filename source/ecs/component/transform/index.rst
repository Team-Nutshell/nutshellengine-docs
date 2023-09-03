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

Notes
-----

When an :doc:`/ecs/entity/index` is created, a Transform Component is automatically created and assigned to this Entity.

The Transform component defines the Entity's world position, rotation and scale.