load
====

:doc:`/types/AudioModuleInterface/index`::loadSound

Loads a sound in the :doc:`/module/audio_module/index` and returns a unique identifier to this sound.

Declaration
-----------

.. code-block:: cpp

	virtual SoundID load(const Sound& sound) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - filePath
	  - const :doc:`/types/Sound/index`\&
	  - The sound to load in the :doc:`/module/audio_module/index`.

Returns
-------

A unique :doc:`/types/SoundID/index` identifier.