ColliderBox
===========

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
	* - center
	  - :doc:`/types/Math/index`::vec3
	  - The box's center in **object-space**.
	* - halfExtent
	  - :doc:`/types/Math/index`::vec3
	  - The half of the box's size on each axis (x, y and z).
	* - rotation
	  - :doc:`/types/Math/index`::vec3
	  - The box's rotation on each axis (x, y and z) in radians.

Notes
-----

.. image:: /assets/collider_box.png

ColliderBox defines an **Oriented Bounding Box** collider using a center defined in **object-space**, the half of each axis extent (half the size of the box) and the rotation on each axis.