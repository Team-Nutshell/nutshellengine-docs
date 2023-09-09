setEntityName
=============

:doc:`/types/ECS/index`::setEntityName

Sets a name to an :doc:`/entity_component_system/entity/index`.

Declaration
-----------

.. code-block:: cpp

	void setEntityName(Entity entity, const std::string& name);

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
	  - The Entity to set the name on.
	* - name
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - The name to give to the Entity.

Returns
-------

None.

Notes
-----

The Entity names are **unique**, which signifies that two :doc:`Entities </entity_component_system/entity/index>` **can not** have the same name.