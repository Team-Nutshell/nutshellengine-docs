ColliderCapsule
===============

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
	* - base
	  - :doc:`/types/Math/index`::vec3
	  - The capsule's base in **object-space**.
	* - tip
	  - :doc:`/types/Math/index`::vec3
	  - The capsule's tip in **object-space**.
	* - radius
	  - float
	  - The sphere's radius.

Notes
-----

.. image:: /assets/collider_capsule.png

ColliderCapsule defines a capsule collider using the base and tip of the capsule in **object-space**, and the radius.