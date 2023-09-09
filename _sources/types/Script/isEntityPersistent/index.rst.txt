isEntityPersistent
==================

:doc:`/types/Script/index`::isEntityPersistent

Checks if an :doc:`/entity_component_system/entity/index` is persistent.

Declaration
-----------

.. code-block:: cpp

	bool isEntityPersistent(Entity entity);

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
	  - The Entity to check the persistence flag of.

Returns
-------

``true`` if the Entity is persistent, else, returns ``false``.