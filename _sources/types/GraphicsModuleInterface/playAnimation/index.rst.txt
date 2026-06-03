playAnimation
=============

:doc:`/types/GraphicsModuleInterface/index`::playAnimation

Plays an :doc:`/types/Animation/index` on an :doc:`/entity_component_system/entity/index`.

Declaration
-----------

.. code-block:: cpp

	virtual void playAnimation(Entity entity, Animation* animation, bool looping) = 0;

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
	* - animation
	  - :doc:`/types/Animation/index`\*
	  - The animation to play.
	* - looping
	  - bool
	  - Whether the animation is looping or not.

Returns
-------

None.

Notes
-----

If another :doc:`/types/Animation/index` of ``entity`` is being played, it is getting replaced by the new one.

If the :doc:`/types/Animation/index` is already playing or is paused, it will start over.