createEntity
============

:doc:`/types/Script/index`::createEntity

Creates a new :doc:`/entity_component_system/entity/index`.

Declaration
-----------

.. code-block:: cpp

	Entity createEntity(const std::string& name = "");

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - name
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - The name of the Entity to create. If the name is the empty string ``""``, the Entity will be created without a name.

Returns
-------

A unique identifier for the :doc:`/entity_component_system/entity/index`.

Notes
-----

When created, an :doc:`/entity_component_system/entity/index` already has a :doc:`/entity_component_system/component/Transform/index` Component.

If ``name`` is not the empty string ``""``, the Entity names are **unique**, which signifies that two Entities **can not** have the same name.