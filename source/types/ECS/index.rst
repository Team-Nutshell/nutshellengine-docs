ECS
===

*Inherits* :doc:`/types/ECSInterface/index`.

Functions
---------

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Name
	  - Description
	* - :doc:`/types/ECS/createEntity/index`
	  - Creates a new :doc:`/entity_component_system/entity/index`.
	* - :doc:`/types/ECS/destroyEntity/index`
	  - Destroys an :doc:`/entity_component_system/entity/index`.
	* - :doc:`/types/ECS/destroyAllEntities/index`
	  - Destroys all :doc:`Entities </entity_component_system/entity/index>`.
	* - :doc:`/types/ECS/destroyNonPersistentEntities/index`
	  - Destroys all :doc:`Entities </entity_component_system/entity/index>` not marked as persistent.
	* - :doc:`/types/ECS/entityExists/index`
	  - Checks if an :doc:`/entity_component_system/entity/index` exists.
	* - :doc:`/types/ECS/setEntityName/index`
	  - Sets a name to an :doc:`/entity_component_system/entity/index`.
	* - :doc:`/types/ECS/entityHasName/index`
	  - Checks if an :doc:`/entity_component_system/entity/index` has a name.
	* - :doc:`/types/ECS/getEntityName/index`
	  - Returns the name of the :doc:`/entity_component_system/entity/index`.
	* - :doc:`/types/ECS/findEntityByName/index`
	  - Returns the :doc:`/entity_component_system/entity/index` associated with the name.
	* - :doc:`/types/ECS/setEntityPersistence/index`
	  - Marks or unmarks the :doc:`/entity_component_system/entity/index` as persistent.
	* - :doc:`/types/ECS/isEntityPersistent/index`
	  - Checks if an :doc:`/entity_component_system/entity/index` is persistent.

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