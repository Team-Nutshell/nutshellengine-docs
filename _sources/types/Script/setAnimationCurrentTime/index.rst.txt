setAnimationCurrentTime
=======================

:doc:`/types/Script/index`::setAnimationCurrentTime

Sets the current playing time of an :doc:`/types/Animation/index` played by an :doc:`/entity_component_system/entity/index`.

Declaration
-----------

.. code-block:: cpp

	void setAnimationCurrentTime(Entity entity, float time);

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
	* - time
	  - float
	  - The time to set the current :doc:`/types/Animation/index` to.

Returns
-------

None.

Notes
-----

If ``time`` is greater than the current's :doc:`/types/Animation/index`'s ``duration``, the animation stops.