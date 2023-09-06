getComponent
============

:doc:`/types/ECS/index`::getComponent

Returns an :doc:`/entity_component_system/entity/index`'s :doc:`/entity_component_system/component/index`.

Declaration
-----------

.. code-block:: cpp

	template <typename T>
	T& getComponent(Entity entity);

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
	  - The Entity to get the :doc:`/entity_component_system/component/index` from.

Returns
-------

A const reference to the Component whose type has been passed in template.

Notes
-----

The type of the :doc:`/entity_component_system/component/index` to get must be passed as a template.