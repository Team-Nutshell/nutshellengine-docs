ECSInterface
============

Functions
---------

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Name
	  - Description
	* - :doc:`/types/ECSInterface/createEntity/index`
	  - Creates a new :doc:`/entity_component_system/entity/index`.
	* - :doc:`/types/ECSInterface/destroyEntity/index`
	  - Destroys an :doc:`/entity_component_system/entity/index`.
	* - :doc:`/types/ECSInterface/destroyAllEntities/index`
	  - Destroys all :doc:`Entities </entity_component_system/entity/index>`.
	* - :doc:`/types/ECSInterface/destroyNonPersistentEntities/index`
	  - Destroys all :doc:`Entities </entity_component_system/entity/index>` not marked as persistent.
	* - :doc:`/types/ECSInterface/entityExists/index`
	  - Checks if an :doc:`/entity_component_system/entity/index` exists.
	* - :doc:`/types/ECSInterface/setEntityName/index`
	  - Sets a name to an :doc:`/entity_component_system/entity/index`.
	* - :doc:`/types/ECSInterface/entityHasName/index`
	  - Checks if an :doc:`/entity_component_system/entity/index` has a name.
	* - :doc:`/types/ECSInterface/getEntityName/index`
	  - Returns the name of the :doc:`/entity_component_system/entity/index`.
	* - :doc:`/types/ECSInterface/findEntityByName/index`
	  - Returns the :doc:`/entity_component_system/entity/index` associated with the name.
	* - :doc:`/types/ECSInterface/setEntityPersistence/index`
	  - Marks or unmarks the :doc:`/entity_component_system/entity/index` as persistent.
	* - :doc:`/types/ECSInterface/isEntityPersistent/index`
	  - Checks if an :doc:`/entity_component_system/entity/index` is persistent.
	* - :doc:`/types/ECSInterface/addEntityToEntityGroup/index`
	  - Adds an :doc:`/entity_component_system/entity/index` to an Entity Group.
	* - :doc:`/types/ECSInterface/removeEntityFromEntityGroup/index`
	  - Removes an :doc:`/entity_component_system/entity/index` from an Entity Group.
	* - :doc:`/types/ECSInterface/entityGroupExists/index`
	  - Checks if an Entity Group exists.
	* - :doc:`/types/ECSInterface/isEntityInEntityGroup/index`
	  - Checks if an :doc:`/entity_component_system/entity/index` is in an Entity Group.
	* - :doc:`/types/ECSInterface/getEntitiesInEntityGroup/index`
	  - Returns the :doc:`Entities </entity_component_system/entity/index>` in an Entity Group.
	* - :doc:`/types/ECSInterface/getEntityGroupsOfEntity/index`
	  - Returns the Entity Groups of an :doc:`/entity_component_system/entity/index`.
	* - :doc:`/types/ECSInterface/addComponent/index`
	  - Adds a :doc:`/entity_component_system/component/index` to an :doc:`/entity_component_system/entity/index`.
	* - :doc:`/types/ECSInterface/removeComponent/index`
	  - Removes a :doc:`/entity_component_system/component/index` from an :doc:`/entity_component_system/entity/index`.
	* - :doc:`/types/ECSInterface/hasComponent/index`
	  - Checks if an :doc:`/entity_component_system/entity/index` has a certain :doc:`/entity_component_system/component/index`.
	* - :doc:`/types/ECSInterface/getComponent/index`
	  - Returns an :doc:`/entity_component_system/entity/index`'s :doc:`/entity_component_system/component/index`.
	* - :doc:`/types/ECSInterface/getComponentID/index`
	  - Returns a :doc:`/entity_component_system/component/index`'s identifier.

.. toctree::
	:hidden:

	./createEntity/index.rst
	./destroyEntity/index.rst
	./destroyAllEntities/index.rst
	./destroyNonPersistentEntities/index.rst
	./entityExists/index.rst
	./setEntityName/index.rst
	./entityHasName/index.rst
	./getEntityName/index.rst
	./findEntityByName/index.rst
	./setEntityPersistence/index.rst
	./isEntityPersistent/index.rst
	./addEntityToEntityGroup/index.rst
	./removeEntityFromEntityGroup/index.rst
	./entityGroupExists/index.rst
	./isEntityInEntityGroup/index.rst
	./getEntitiesInEntityGroup/index.rst
	./getEntityGroupsOfEntity/index.rst
	./addComponent/index.rst
	./removeComponent/index.rst
	./hasComponent/index.rst
	./getComponent/index.rst
	./getComponentID/index.rst