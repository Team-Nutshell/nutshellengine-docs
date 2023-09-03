entityHasName
=============

Script::entityHasName

Declaration
-----------

.. code-block:: cpp

	bool entityHasName(Entity entity);

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
	  - The Entity to check the existence of a name of.

Returns
-------

``true`` if the Entity has a name, else, returns ``false``.