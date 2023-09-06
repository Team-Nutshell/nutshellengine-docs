ECS
===

Functions
---------

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Name
	  - Description
	* - :doc:`/entity_component_system/ecs/createEntity/index`
	  - Creates a new :doc:`/entity_component_system/entity/index`.
	* - :doc:`/entity_component_system/ecs/destroyEntity/index`
	  - Destroys an :doc:`/entity_component_system/entity/index`.
	* - :doc:`/entity_component_system/ecs/destroyAllEntities/index`
	  - Destroys all Entities.
	* - :doc:`/entity_component_system/ecs/destroyNonPersistentEntities/index`
	  - Destroys all Entities not marked as persistent.
	* - :doc:`/entity_component_system/ecs/entityExists/index`
	  - Checks if an :doc:`/entity_component_system/entity/index` exists.
	* - :doc:`/entity_component_system/ecs/setEntityName/index`
	  - Sets a name to an :doc:`/entity_component_system/entity/index`.
	* - :doc:`/entity_component_system/ecs/entityHasName/index`
	  - Checks if an :doc:`/entity_component_system/entity/index` has a name.
	* - :doc:`/entity_component_system/ecs/getEntityName/index`
	  - Returns the name of the :doc:`/entity_component_system/entity/index`.
	* - :doc:`/entity_component_system/ecs/findEntityByName/index`
	  - Returns the :doc:`/entity_component_system/entity/index` associated with the name.
	* - :doc:`/entity_component_system/ecs/setEntityPersistence/index`
	  - Marks or unmarks the :doc:`/entity_component_system/entity/index` as persistent.
	* - :doc:`/entity_component_system/ecs/isEntityPersistent/index`
	  - Checks if an :doc:`/entity_component_system/entity/index` is persistent.
	* - :doc:`/entity_component_system/ecs/addComponent/index`
	  - Adds a :doc:`/entity_component_system/component/index` to an :doc:`/entity_component_system/entity/index`.
	* - :doc:`/entity_component_system/ecs/removeComponent/index`
	  - Removes a :doc:`/entity_component_system/component/index` from an :doc:`/entity_component_system/entity/index`.
	* - :doc:`/entity_component_system/ecs/hasComponent/index`
	  - Checks if an :doc:`/entity_component_system/entity/index` has a certain :doc:`/entity_component_system/component/index`.
	* - :doc:`/entity_component_system/ecs/getComponent/index`
	  - Returns an :doc:`/entity_component_system/entity/index`'s :doc:`/entity_component_system/component/index`.
	* - :doc:`/entity_component_system/ecs/getComponentID/index`
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
	./addComponent/index.rst
	./removeComponent/index.rst
	./hasComponent/index.rst
	./getComponent/index.rst
	./getComponentID/index.rst