getPlayingAnimation
===================

:doc:`/types/GraphicsModuleInterface/index`::getPlayingAnimation

Returns the index of the animation played by an :doc:`/entity_component_system/entity/index`.

Declaration
-----------

.. code-block:: cpp

	virtual uint32_t getPlayingAnimation(Entity entity) = 0;

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
	  - The :doc:`/entity_component_system/entity/index` to get the playing :doc:`/types/Animation/index`'s index of. It must have a :doc:`/types/Renderable/index` :doc:`/types/Component/index`.

Returns
-------

The index of the currently playing animation. If no animation is playing, returns ``0xFFFFFFFF``.