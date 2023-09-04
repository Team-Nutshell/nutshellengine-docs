entityExists
============

:doc:`/scripting/script/index`::entityExists

Declaration
-----------

.. code-block:: cpp

	bool entityExists(Entity entity);

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
	  - The Entity to check the existence of.

Returns
-------

``true`` if the Entity exists, else, returns ``false``.