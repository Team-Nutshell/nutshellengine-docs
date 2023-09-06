hasComponent
============

:doc:`/entity_component_system/ecs/index`::hasEntityComponent

Checks if an :doc:`/entity_component_system/entity/index` has a certain :doc:`/entity_component_system/component/index`.

Declaration
-----------

.. code-block:: cpp

	template <typename T>
	bool hasComponent(Entity entity);

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
	  - The Entity to check the possession of the :doc:`/entity_component_system/component/index` on.

Returns
-------

``true`` if the Entity has a Component of the same type as the one passed in template, else, returns ``false``.

Notes
-----

The type of the :doc:`/entity_component_system/component/index` to check must be passed as a template.