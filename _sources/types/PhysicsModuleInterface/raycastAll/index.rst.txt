raycastAll
==========

:doc:`/types/PhysicsModuleInterface/index`::raycastAll

Casts a ray and returns information about the hit :doc:`Entities </entity_component_system/entity/index>`.

Declaration
-----------

.. code-block:: cpp

	virtual std::vector<std::pair<Entity, RaycastInformation>> raycastAll(const Math::vec3& rayOrigin, const Math::vec3& rayDirection, float tMin, float tMax) = 0;

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
	* - tMin
	  - float
	  - The minimum distance to check.
	* - tMax
	  - float
	  - The maximum distance to check.

Returns
-------

An `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_ of an `std::pair <https://en.cppreference.com/w/cpp/utility/pair>` of :doc:`/entity_component_system/entity/index` and :doc:`/types/RaycastInformation/index` containing information about the hit :doc:`Entities </entity_component_system/entity/index>`.

The returned list is sorted from the closest to the furthest object. ``RaycastInformation::hasIntersected`` will always be ``true``.

If no :doc:`/entity_component_system/entity/index` has been hit, the returned list is empty.