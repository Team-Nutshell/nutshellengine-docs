IntersectionInformation
=======================

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - hasIntersected
	  - bool
	  - ``true`` when the two objects collided.
	* - normal
	  - :doc:`/types/Math/index`::vec3
	  - The intersection normal from the first collider to the second.
	* - depth
	  - float
	  - The penetration depth of the two collided objects.
	* - relativePoints
	  - `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_\<`std::pair <https://en.cppreference.com/w/cpp/utility/pair>`_\<:doc:`/types/Math/index`::vec3>>
	  - The pairs of relative intersection points of the two collided objects, in **local-space**. The first element of the pair is the intersection point relative to the first object's center and the second element of the pair is the intersection point relative to the second object's center.
