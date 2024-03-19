raycast
=======

:doc:`/types/Script/index`::raycast

Casts a ray and returns information about the intersection between the ray and the :doc:`/types/ColliderShape/index`.

Declaration
-----------

.. code-block:: cpp

	RaycastInformation raycast(const Math::vec3& rayOrigin, const Math::vec3& rayDirection, const ColliderShape* shape, float tMin = 0.0001f, float tMax = 1000000.0f);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - rayOrigin
	  - const :doc:`/types/Math/index`::vec3&
	  - The origin position of the ray, in **world-space**.
	* - rayDirection
	  - const :doc:`/types/Math/index`::vec3&
	  - The direction of the ray.
	* - shape
	  - const :doc:`/types/ColliderShape/index`\*
	  - The shape to test the ray intersection on.
	* - tMin
	  - float
	  - The minimum distance to check.
	* - tMax
	  - float
	  - The maximum distance to check.

Returns
-------

A :doc:`/types/RaycastInformation/index` containing information about the intersection. If there is no intersection between the ray and the shape, ``RaycastInformation::hasIntersected`` will be ``false``.