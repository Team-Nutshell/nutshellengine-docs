playAnimation
=============

:doc:`/types/Script/index`::playAnimation

Plays an :doc:`/types/Animation/index` on an :doc:`/entity_component_system/entity/index`.

Declaration
-----------

.. code-block:: cpp

	void playAnimation(Entity entity, uint32_t animationIndex);

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
	  - The :doc:`/entity_component_system/entity/index` to play the :doc:`/types/Animation/index` of. It must have a :doc:`/types/Renderable/index` :doc:`/types/Component/index`.
	* - animationIndex
	  - uint32_t
	  - The animation to play, indexed on ``entity``\'s :doc:`/types/Renderable/index`'s ``model``'s :doc:`/types/Animation/index` list.

Returns
-------

None.

Notes
-----

If another :doc:`/types/Animation/index` of ``entity`` is being played, it is getting replaces by the new one.

If the :doc:`/types/Animation/index` is already playing, this function does nothing.

If the :doc:`/types/Animation/index` is paused, with the :doc:`/scripting/api/index`'s function :doc:`/types/Script/pauseAnimation/index` or the :doc:`/module/graphics_module/index`'s :doc:`/types/GraphicsModuleInterface/pauseAnimation/index` function, it will resume at the moment it was paused.