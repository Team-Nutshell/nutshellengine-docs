setAnimationSpeed
=================

:doc:`/types/Script/index`::setAnimationSpeed

Sets the speed of an :doc:`/types/Animation/index` played by an :doc:`/entity_component_system/entity/index`.

Declaration
-----------

.. code-block:: cpp

	void setAnimationCurrentTime(Entity entity, float newSpeed);

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
	* - newSpeed
	  - float
	  - The speed to play the current :doc:`/types/Animation/index` at.

Returns
-------

None.

Notes
-----

If ``newSpeed`` is negative, the animation plays in reverse.