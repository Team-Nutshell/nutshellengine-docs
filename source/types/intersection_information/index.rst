IntersectionInformation
=======================

Declaration
-----------

.. code-block:: cpp

	struct IntersectionInformation {
		bool hasIntersected = false;
		Math::vec3 intersectionNormal = { 0.0f, 0.0f, 0.0f };
		float intersectionDepth = 0.0f;
	};

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
	* - intersectionNormal
	  - Math::vec3
	  - The intersection normal from the second collider to the first.
	* - intersectionDepth
	  - float
	  - The penetration depth of the two collided objects.
