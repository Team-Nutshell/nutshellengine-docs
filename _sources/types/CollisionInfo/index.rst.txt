CollisionInfo
=============

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - otherEntity
	  - :doc:`/entity_component_system/entity/index`
	  - The :doc:`/entity_component_system/entity/index` that collided with the current :doc:`/entity_component_system/entity/index`.
	* - normal
	  - :doc:`/types/Math/index`::vec3
	  - The normal of the intersection.
	* - depth
	  - float
	  - The depth of the intersection.
	* - relativePoints
	  - float
	  - `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_\<:doc:`/types/Math/index`::vec3>
	  - The list of intersection points relative to the current :doc:`/entity_component_system/entity/index`, in **local-space**.