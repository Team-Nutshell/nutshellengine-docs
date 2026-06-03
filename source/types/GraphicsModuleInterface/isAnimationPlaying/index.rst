isAnimationPlaying
==================

:doc:`/types/GraphicsModuleInterface/index`::isAnimationPlaying

Checks if an :doc:`/entity_component_system/entity/index` is currently playing a certain :doc:`/types/Animation/index`.

Declaration
-----------

.. code-block:: cpp

	virtual bool isAnimationPlaying(Entity entity, Animation* animation) = 0;

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
	* - animation
	  - :doc:`/types/Animation/index`\*
	  - The animation to check the status of.

Returns
-------

``true`` if the :doc:`/types/Animation/index` is currently playing on the :doc:`/entity_component_system/entity/index`, else, returns ``false``.