addEntityComponent
==================

:doc:`/types/Script/index`::addEntityComponent

Adds a :doc:`/entity_component_system/component/index` to an :doc:`/entity_component_system/entity/index`.

Declaration
-----------

.. code-block:: cpp

	template <typename T>
	void addEntityComponent(Entity entity, T component);

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
	  - The Entity to add the Component to.
	* - component
	  - *T* (:doc:`/entity_component_system/component/index`)
	  - The component to add to the Entity.

Returns
-------

None.