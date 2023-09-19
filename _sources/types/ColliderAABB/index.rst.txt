ColliderAABB
============

*Inherits* :doc:`/types/ColliderShape/index`.

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - min
	  - :doc:`/types/Math/index`::vec3
	  - The "minimal" corner, which contains the minimum x, y and z.
	* - max
	  - :doc:`/types/Math/index`::vec3
	  - The "maximal" corner, which contains the maximum x, y and z.

Notes
-----

.. image:: /assets/collider_aabb.png

ColliderAABB defines an **Axis-Aligned Bounding Box** collider using two positions : the "minimal" and the "maximal" corners. These positions are defined in **object-space**.