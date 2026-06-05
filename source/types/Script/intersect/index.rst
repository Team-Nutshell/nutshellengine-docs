intersect
=========

:doc:`/types/Script/index`::intersect

Returns information about the intersection of two :doc:`ColliderShapes </types/ColliderShape/index>`.

Declaration
-----------

.. code-block:: cpp

	IntersectionInformation intersect(const ColliderShape& collider1, const ColliderShape& collider2);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - collider1
	  - const :doc:`/types/ColliderShape/index`\&
	  - The first collider.
	* - collider2
	  - const :doc:`/types/ColliderShape/index`\&
	  - The second collider.

Returns
-------

An :doc:`/types/IntersectionInformation/index` containing information about the intersection between ``collider1`` and ``collider2``. If there is no intersection between these two colliders, ``IntersectionInformation::hasIntersected`` will be ``false``.