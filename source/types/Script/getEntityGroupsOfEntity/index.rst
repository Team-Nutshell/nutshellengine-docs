getEntityGroupsOfEntity
=======================

:doc:`/types/Script/index`::getEntityGroupsOfEntity

Returns the Entity Groups of an :doc:`/entity_component_system/entity/index`.

Declaration
-----------

.. code-block:: cpp

	std::set<std::string> getEntityGroupsOfEntity(Entity entity);

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
	  - The Entity to get the Entity Groups of.

Returns
-------

The Entity Groups the ``entity`` belongs to. If ``entity`` has no Entity Group, the returned `std::set <https://en.cppreference.com/w/cpp/container/set>`_\<`std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_> is empty.