resumeAnimation
===============

:doc:`/types/GraphicsModuleInterface/index`::resumeAnimation

Resumes an :doc:`/types/Animation/index` on an :doc:`/entity_component_system/entity/index`.

Declaration
-----------

.. code-block:: cpp

	virtual void resumeAnimation(Entity entity) = 0;

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
	  - The animation to resume, indexed on ``entity``\'s :doc:`/types/Renderable/index`'s ``model``'s :doc:`/types/Animation/index` list.

Returns
-------

None.