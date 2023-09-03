ColliderCapsule
===============

*Inherits* :doc:`/structures/collider_shape/index`.

Declaration
-----------

.. code-block:: cpp

	struct ColliderCapsule: public ColliderShape {
		ColliderCapsule() : ColliderShape(ColliderShapeType::Capsule) {}

		Math::vec3 base = { 0.0f, 0.0f, 0.0f };
		Math::vec3 tip = { 0.0f, 0.0f, 0.0f };
		float radius = 0.0f;
	};

Notes
-----

.. image:: /assets/collider_capsule.png

ColliderCapsule defines a capsule collider using the base and tip of the capsule in **object-space**, and the radius.