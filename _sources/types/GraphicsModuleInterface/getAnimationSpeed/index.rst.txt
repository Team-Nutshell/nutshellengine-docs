getAnimationSpeed
=================

:doc:`/types/GraphicsModuleInterface/index`::getAnimationSpeed

Returns the speed of an :doc:`/types/Animation/index` played by an :doc:`/entity_component_system/entity/index`.

Declaration
-----------

.. code-block:: cpp

	virtual float getAnimationSpeed(Entity entity) = 0;

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
	  - The :doc:`/entity_component_system/entity/index` the :doc:`/types/Animation/index` is played on. It must have a :doc:`/types/Renderable/index` :doc:`/types/Component/index`.

Returns
-------

The speed of an animation, **in seconds**.