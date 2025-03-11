removeEntityFromEntityGroup
===========================

:doc:`/types/ECS/index`::removeEntityFromEntityGroup

Removes an :doc:`/entity_component_system/entity/index` from an Entity Group.

Declaration
-----------

.. code-block:: cpp

	void removeEntityFromEntityGroup(Entity entity, const std::string& entityGroupName);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - entity
	  - :doc:`/entity_component_system/entity/index`
	  - The Entity to remove from the Entity Group.
	* - entityGroupName
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - The name of the Entity Group to remove the Entity from.

Returns
-------

None.