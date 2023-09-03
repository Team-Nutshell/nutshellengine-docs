ColliderSphere
==============

*Inherits* :doc:`/structures/collider_shape/index`.

Declaration
-----------

.. code-block:: cpp

	struct ColliderSphere: public ColliderShape {
		ColliderSphere() : ColliderShape(ColliderShapeType::Sphere) {}

		Math::vec3 center = { 0.0f, 0.0f, 0.0f };
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
	* - center
	  - Math::vec3
	  - The sphere's center in **object-space**.
	* - radius
	  - float
	  - The sphere's radius.

Notes
-----

.. image:: /assets/collider_sphere.png

ColliderSphere defines a spherical collider using a center position in **object-space** and a radius.