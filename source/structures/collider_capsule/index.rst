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

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - base
	  - Math::vec3
	  - The capsule's base in **object-space**.
	* - tip
	  - Math::vec3
	  - The capsule's tip in **object-space**.
	* - radius
	  - float
	  - The sphere's radius.

Notes
-----

.. image:: /assets/collider_capsule.png

ColliderCapsule defines a capsule collider using the base and tip of the capsule in **object-space**, and the radius.