destroyAllEntities
==================

:doc:`/types/ECSInterface/index`::destroyAllEntities

Destroys all :doc:`Entities </entity_component_system/entity/index>`.

Declaration
-----------

.. code-block:: cpp

	virtual void destroyAllEntities() = 0;

Parameters
----------

None.

Returns
-------

None.

Notes
-----

This function will destroy the calling Entity. The rest of the script **must not** reference any function or variable belonging to this Entity. It is safer to ``return`` right after calling this function:

.. code-block:: cpp

	destroyAllEntities();
	return;
