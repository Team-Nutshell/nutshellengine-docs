destroyNonPersistentEntities
============================

Script::destroyNonPersistentEntities

Declaration
-----------

.. code-block:: cpp

	void destroyNonPersistentEntities();

Parameters
----------

None.

Returns
-------

None.

Notes
-----

This function will destroy all non-persistent Entities, potentially including the Entity calling this function.

If this is the case, the rest of the script **must not** reference any function or variable belonging to this Entity. It is safer to ``return`` right after calling this function:

.. code-block:: cpp

	destroyNonPersistentEntities();
	return;
