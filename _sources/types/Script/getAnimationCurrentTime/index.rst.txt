getAnimationCurrentTime
=======================

:doc:`/types/Script/index`::getAnimationCurrentTime

Returns the current playing time of an :doc:`/types/Animation/index` played by an :doc:`/entity_component_system/entity/index`.

Declaration
-----------

.. code-block:: cpp

	float getAnimationCurrentTime(Entity entity);

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

The current time of an animation, **in seconds**.