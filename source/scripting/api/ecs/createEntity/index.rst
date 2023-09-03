createEntity
============

Script::createEntity

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

A unique identifier for the :doc:`/ecs/entity/index`.

Notes
-----

When created, an :doc:`/ecs/entity/index` already has a :doc:`/ecs/component/transform/index` Component.

If ``name`` is not the empty string ``""``, the Entity names are **unique**, which signifies that two Entities **can not** have the same name.