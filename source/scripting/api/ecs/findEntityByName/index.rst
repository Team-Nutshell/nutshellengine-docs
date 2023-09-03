findEntityByName
================

ScriptingAPI::findEntityByName

Declaration
-----------

.. code-block:: cpp

	Entity findEntityByName(const std::string& name);

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
	  - The name of the Entity.

Returns
-------

The :doc:`/ecs/entity/index` if the name is associated with an Entity, else, returns ``NTSHENGN_ENTITY_UNKNOWN``.