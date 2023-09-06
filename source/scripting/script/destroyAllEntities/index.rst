destroyAllEntities
==================

:doc:`/scripting/script/index`::destroyAllEntities

Destroys all Entities.

Declaration
-----------

.. code-block:: cpp

	void destroyAllEntities();

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
