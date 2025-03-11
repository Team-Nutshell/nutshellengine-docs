addEntityToEntityGroup
======================

:doc:`/types/ECSInterface/index`::addEntityToEntityGroup

Adds an :doc:`/entity_component_system/entity/index` to an Entity Group.

Declaration
-----------

.. code-block:: cpp

	virtual void addEntityToEntityGroup(Entity entity, const std::string& entityGroupName) = 0;

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
	  - The Entity to add to the Entity Group.
	* - entityGroupName
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - The name of the Entity Group to add the Entity to.

Returns
-------

None.