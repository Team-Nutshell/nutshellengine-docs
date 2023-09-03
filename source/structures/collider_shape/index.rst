ColliderShape
=============

Declaration
-----------

.. code-block:: cpp

	struct ColliderShape {
		ColliderShape(const ColliderShapeType shapeType) : type(shapeType) {}

		ColliderShapeType getType() const { return type; }

	private:
		ColliderShapeType type = ColliderShapeType::Unknown;
	};

Notes
-----

ColliderShape contains a :doc:`/structures/collider_shape_type/index` to differentiate the different shape types.