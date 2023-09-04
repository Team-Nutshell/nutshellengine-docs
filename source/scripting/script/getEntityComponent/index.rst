getEntityComponent
==================

:doc:`/scripting/script/index`::getEntityComponent

Declaration
-----------

.. code-block:: cpp

	template <typename T>
	T& getEntityComponent(Entity entity);

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
	  - The Entity to get the :doc:`/ecs/component/index` from.

Returns
-------

A const reference to the Component whose type has been passed in template.

Notes
-----

The type of the :doc:`/ecs/component/index` to get must be passed as a template.