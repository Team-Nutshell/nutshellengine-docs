ColliderAABB
============

*Inherits* :doc:`/structures/collider_shape/index`.

Declaration
-----------

.. code-block:: cpp

	struct ColliderAABB: public ColliderShape {
		ColliderAABB() : ColliderShape(ColliderShapeType::AABB) {}

		Math::vec3 min = { 0.0f, 0.0f, 0.0f };
		Math::vec3 max = { 0.0f, 0.0f, 0.0f };
	};

Notes
-----

.. image:: /assets/collider_aabb.png

ColliderAABB defines an **Axis-Aligned Bounding Box** collider using two positions : the "minimal" and the "maximal" corners. These positions are defined in **object-space**.