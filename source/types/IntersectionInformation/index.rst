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
	  - The intersection normal from the second collider to the first.
	* - depth
	  - float
	  - The penetration depth of the two collided objects.
	* - points
	  - `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_\<:doc:`/types/Math/index`::vec3>
	  - The intersection points of the two collided objects, in **world-space**.
