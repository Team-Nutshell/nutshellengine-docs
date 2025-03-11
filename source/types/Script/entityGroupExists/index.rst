entityGroupExists
=================

:doc:`/types/Script/index`::entityGroupExists

Checks if an Entity Group exists.

Declaration
-----------

.. code-block:: cpp

	bool entityGroupExists(const std::string& entityGroupName);

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
	  - The Entity Group to check the existence of.

Returns
-------

``true`` if at least one :doc:`/entity_component_system/entity/index` is in the Entity Group, else, returns ``false``.