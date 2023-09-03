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

Functions
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Description
	* - :doc:`/types/collider_shape/getType/index`
	  - Returns the ``type`` of the collider.

Notes
-----

ColliderShape contains a :doc:`/types/collider_shape_type/index` to differentiate the different shape types.