addEntityComponent
==================

:doc:`/scripting/script/index`::addEntityComponent

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
	  - :doc:`/ecs/entity/index`
	  - The Entity to add the Component to.
	* - component
	  - *T* (:doc:`/ecs/component/index`)
	  - The component to add to the Entity.

Returns
-------

None.