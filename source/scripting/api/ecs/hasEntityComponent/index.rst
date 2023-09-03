hasEntityComponent
==================

Script::hasEntityComponent

Declaration
-----------

.. code-block:: cpp

	template <typename T>
	bool hasEntityComponent(Entity entity);

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
	  - The Entity to check the possession of the :doc:`/ecs/component/index` on.

Returns
-------

``true`` if the Entity has a Component of the same type as the one passed in template, else, returns ``false``.

Notes
-----

The type of the :doc:`/ecs/component/index` to check must be passed as a template.