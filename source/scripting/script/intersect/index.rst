intersect
=========

:doc:`/scripting/script/index`::intersect

Returns information about the intersection of two :doc:`/types/ColliderShape/index`\s.

Declaration
-----------

.. code-block:: cpp

	IntersectionInformation intersect(const ColliderShape* shape1, const ColliderShape* shape2);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - shape1
	  - const :doc:`/types/ColliderShape/index`\*
	  - The first shape.
	* - shape2
	  - const :doc:`/types/ColliderShape/index`\*
	  - The second shape.

Returns
-------

An :doc:`/types/IntersectionInformation/index` containing information about the intersection between ``shape1`` and ``shape2``. If there is no intersection between these two shapes, ``IntersectionInformation::hasIntersected`` will be ``false``.