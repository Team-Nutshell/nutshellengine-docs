pauseAnimation
==============

:doc:`/types/GraphicsModuleInterface/index`::pauseAnimation

Pauses an :doc:`/types/Animation/index` of an :doc:`/entity_component_system/entity/index`.

Declaration
-----------

.. code-block:: cpp

	void pauseAnimation(Entity entity);

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
	  - The :doc:`/entity_component_system/entity/index` to pause the :doc:`/types/Animation/index` of. It must have a :doc:`/types/Renderable/index` :doc:`/types/Component/index`.

Returns
-------

None.