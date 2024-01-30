onCollisionExit
===============

:doc:`/types/ScriptBase/index`::onCollisionExit

Is executed the frame an :doc:`/entity_component_system/entity/index`'s :doc:`/types/Collidable/index` :doc:`/entity_component_system/component/index` stops colliding with another's :doc:`/entity_component_system/entity/index`'s :doc:`/types/Collidable/index` :doc:`/entity_component_system/component/index`.

Declaration
-----------

.. code-block:: cpp

	virtual void onCollisionExit(CollisionInfo collisionInfo);

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

This function is called the frame :doc:`/entity_component_system/entity/index` and ``collisionInfo.otherEntity`` stop colliding. As both :doc:`Entities </entity_component_system/entity/index>` are not colliding anymore, ``collisionInfo.normal``, ``collisionInfo.depth`` and ``collisionInfo.relativePoints`` will be the same as the previous frame's :doc:`/types/ScriptBase/index`'s :doc:`/types/ScriptBase/onCollisionEnter/index` call or :doc:`/types/ScriptBase/index`'s :doc:`/types/ScriptBase/onCollisionStill/index` call, depending on which one was called last.