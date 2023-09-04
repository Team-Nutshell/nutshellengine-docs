removeEntityComponent
=====================

:doc:`/scripting/script/index`::removeEntityComponent

Declaration
-----------

.. code-block:: cpp

	template <typename T>
	void removeEntityComponent(Entity entity);

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
	  - The Entity to remove the Component from.

Returns
-------

None.

Notes
-----

The type of the :doc:`/ecs/component/index` to remove must be passed as a template.