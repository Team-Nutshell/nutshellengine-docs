isAnimationPlaying
==================

:doc:`/types/GraphicsModuleInterface/index`::isAnimationPlaying

Checks if an :doc:`/entity_component_system/entity/index` is currently playing a certain :doc:`/types/Animation/index`.

Declaration
-----------

.. code-block:: cpp

	virtual bool isAnimationPlaying(Entity entity, uint32_t animationIndex) = 0;

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
	  - The :doc:`/entity_component_system/entity/index` to check the :doc:`/types/Animation/index`'s status of. It must have a :doc:`/types/Renderable/index` :doc:`/types/Component/index`.
	* - animationIndex
	  - uint32_t
	  - The animation to check the status of, indexed on ``entity``\'s :doc:`/types/Renderable/index`'s ``model``'s :doc:`/types/Animation/index` list.

Returns
-------

``true`` if the :doc:`/types/Animation/index` is currently playing on the :doc:`/entity_component_system/entity/index`, else, returns ``false``.