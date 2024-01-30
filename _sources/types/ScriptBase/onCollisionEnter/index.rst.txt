onCollisionEnter
================

:doc:`/types/ScriptBase/index`::onCollisionEnter

Is executed the frame an :doc:`/entity_component_system/entity/index`'s :doc:`/types/Collidable/index` :doc:`/entity_component_system/component/index` collides with another's :doc:`/entity_component_system/entity/index`'s :doc:`/types/Collidable/index` :doc:`/entity_component_system/component/index`.

Declaration
-----------

.. code-block:: cpp

	virtual void onCollisionEnter(CollisionInfo collisionInfo);

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

This function is called the first frame the current :doc:`/entity_component_system/entity/index` and ``collisionInfo.otherEntity`` collide. It will be called again when both :doc:`Entities </entity_component_system/entity/index>` will stop colliding and collide again.