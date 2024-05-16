entityExists
============

:doc:`/types/ECSInterface/index`::entityExists

Checks if an :doc:`/entity_component_system/entity/index` exists.

Declaration
-----------

.. code-block:: cpp

	virtual bool entityExists(Entity entity) = 0;

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
	  - The Entity to check the existence of.

Returns
-------

``true`` if the Entity exists, else, returns ``false``.