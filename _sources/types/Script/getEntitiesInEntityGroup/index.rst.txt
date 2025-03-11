getEntitiesInEntityGroup
========================

:doc:`/types/Script/index`::getEntitiesInEntityGroup

Returns the :doc:`Entities </entity_component_system/entity/index>` in an Entity Group.

Declaration
-----------

.. code-block:: cpp

	std::set<Entity> getEntitiesInEntityGroup(const std::string& entityGroupName);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - entityGroupName
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - The name of the Entity Group to get the Entities from.

Returns
-------

The :doc:`Entities </entity_component_system/entity/index>` that belong to the Entity Group with name ``entityGroupName``. If the Entity Group does not exist, the returned `std::set <https://en.cppreference.com/w/cpp/container/set>`_\<:doc:`/entity_component_system/entity/index`> is empty.