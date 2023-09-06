getEntityName
=============

:doc:`/types/ECS/index`::getEntityName

Returns the name of the :doc:`/entity_component_system/entity/index`.

Declaration
-----------

.. code-block:: cpp

	std::string getEntityName(Entity entity);

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
	  - The Entity to get the name of.

Returns
-------

The name of Entity if it has one, else, returns the empty string ``""``.