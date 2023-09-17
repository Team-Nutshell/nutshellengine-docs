setSoundListenerEntity
======================

:doc:`/types/Script/index`::setSoundListenerEntity

Sets the :doc:`/entity_component_system/entity/index` that will be the sound listener.

Declaration
-----------

.. code-block:: cpp

	void setSoundListenerEntity(Entity entity);

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
	  - The :doc:`/entity_component_system/entity/index` that will be the sound listener.

Returns
-------

None.

Notes
-----

If there is no listener :doc:`/entity_component_system/entity/index`, all sounds played with the :doc:`/module/audio_module/index`'s :doc:`/types/AudioModuleInterface/playSoundAtPosition/index` or the :doc:`/scripting/api/index`'s :doc:`/types/Script/playSoundAtPosition/index` functions will be played globally.