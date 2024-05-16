destroyEntity
=============

:doc:`/types/ECSInterface/index`::destroyEntity

Destroys an :doc:`/entity_component_system/entity/index`.

Declaration
-----------

.. code-block:: cpp

	virtual void destroyEntity(Entity entity) = 0;

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
	  - The Entity to destroy.

Returns
-------

None.

Notes
-----

If the :doc:`/entity_component_system/entity/index` is self-destructing, which means that this function's parameter is the Entity's own identifier, for example:

.. code-block:: cpp

	destroyEntity(entityID);

The rest of the script **must not** reference any function or variable belonging to this Entity. It is safer to ``return`` right after self-destructing:

.. code-block:: cpp

	destroyEntity(entityID);
	return;
