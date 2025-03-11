isEntityInEntityGroup
=====================

:doc:`/types/ECSInterface/index`::isEntityInEntityGroup

Checks if an :doc:`/entity_component_system/entity/index` is in an Entity Group.

Declaration
-----------

.. code-block:: cpp

	virtual bool isEntityInEntityGroup(Entity entity, const std::string& entityGroupName) = 0;

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
	  - The Entity to check.
	* - entityGroupName
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - The name of the Entity Group to check if the Entity is in.

Returns
-------

``true`` if ``entity`` is in the Entity Group, else, returns ``false``.