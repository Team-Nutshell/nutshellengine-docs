removeComponent
===============

:doc:`/entity_component_system/ecs/index`::removeEntityComponent

Removes a :doc:`/entity_component_system/component/index` from an :doc:`/entity_component_system/entity/index`.

Declaration
-----------

.. code-block:: cpp

	template <typename T>
	void removeComponent(Entity entity);

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
	  - The Entity to remove the Component from.

Returns
-------

None.

Notes
-----

The type of the :doc:`/entity_component_system/component/index` to remove must be passed as a template.