getEntityName
=============

:doc:`/scripting/script/index`::getEntityName

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
	  - :doc:`/ecs/entity/index`
	  - The Entity to get the name of.

Returns
-------

The name of Entity if it has one, else, returns the empty string ``""``.