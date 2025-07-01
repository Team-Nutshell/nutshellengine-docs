ScriptBase
==========

Functions
---------

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Name
	  - Description
	* - :doc:`/types/ScriptBase/onSceneEnter/index`
	  - Is executed after a new scene is loaded.
	* - :doc:`/types/ScriptBase/onSceneExit/index`
	  - Is executed before a new scene is loaded.
	* - :doc:`/types/ScriptBase/onCollisionEnter/index`
	  - Is executed the frame an :doc:`/entity_component_system/entity/index`'s :doc:`/types/Collidable/index` :doc:`/entity_component_system/component/index` collides with another's :doc:`/entity_component_system/entity/index`'s :doc:`/types/Collidable/index` :doc:`/entity_component_system/component/index`.
	* - :doc:`/types/ScriptBase/onCollisionStill/index`
	  - Is executed during the time an :doc:`/entity_component_system/entity/index`'s :doc:`/types/Collidable/index` :doc:`/entity_component_system/component/index` collides with another's :doc:`/entity_component_system/entity/index`'s :doc:`/types/Collidable/index` :doc:`/entity_component_system/component/index`.
	* - :doc:`/types/ScriptBase/onCollisionExit/index`
	  - Is executed the frame an :doc:`/entity_component_system/entity/index`'s :doc:`/types/Collidable/index` :doc:`/entity_component_system/component/index` stops colliding with another's :doc:`/entity_component_system/entity/index`'s :doc:`/types/Collidable/index` :doc:`/entity_component_system/component/index`.

.. toctree::
	:hidden:

	./onSceneEnter/index.rst
	./onSceneExit/index.rst
	./onCollisionEnter/index.rst
	./onCollisionStill/index.rst
	./onCollisionExit/index.rst