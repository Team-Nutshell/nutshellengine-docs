isEntityPersistent
==================

Script::isEntityPersistent

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
	  - :doc:`/ecs/entity/index`
	  - The Entity to check the persistence flag of.

Returns
-------

``true`` if the Entity is persistent, else, returns ``false``.