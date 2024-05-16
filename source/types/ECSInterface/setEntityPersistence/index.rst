setEntityPersistence
====================

:doc:`/types/ECSInterface/index`::setEntityPersistence

Marks or unmarks the :doc:`/entity_component_system/entity/index` as persistent.

Declaration
-----------

.. code-block:: cpp

	virtual void setEntityPersistence(Entity entity, bool persistent) = 0;

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
	  - The Entity to set the persistence flag on.
	* - persistent
	  - bool
	  - The status of the persistence flag.

Returns
-------

None.