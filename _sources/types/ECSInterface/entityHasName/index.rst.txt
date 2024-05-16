entityHasName
=============

:doc:`/types/ECSInterface/index`::entityHasName

Checks if an :doc:`/entity_component_system/entity/index` has a name.

Declaration
-----------

.. code-block:: cpp

	virtual bool entityHasName(Entity entity) = 0;

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
	  - The Entity to check the existence of a name of.

Returns
-------

``true`` if the Entity has a name, else, returns ``false``.