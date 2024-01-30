onCollisionStill
================

:doc:`/types/ScriptBase/index`::onCollisionStill

Is executed during the time an :doc:`/entity_component_system/entity/index`'s :doc:`/types/Collidable/index` :doc:`/entity_component_system/component/index` collides with another's :doc:`/entity_component_system/entity/index`'s :doc:`/types/Collidable/index` :doc:`/entity_component_system/component/index`.

Declaration
-----------

.. code-block:: cpp

	virtual void onCollisionStill(CollisionInfo collisionInfo);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - collisionInfo
	  - :doc:`/types/CollisionInfo/index`
	  - Information about the collision.

Returns
-------

None.

Notes
-----

This function is called the frame after :doc:`/types/ScriptBase/index`'s :doc:`/types/ScriptBase/onCollisionEnter/index` is called if the current :doc:`/entity_component_system/entity/index` and ``collisionInfo.otherEntity`` are still colliding. It will be called each frame both :doc:`Entities </entity_component_system/entity/index>` collide and will not be called anymore when they will stop colliding.