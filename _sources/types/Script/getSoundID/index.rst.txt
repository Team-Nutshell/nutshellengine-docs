getSoundID
==========

:doc:`/types/Script/index`::getSoundID

Loads a sound in the :doc:`/module/audio_module/index` and returns a unique identifier to this sound.

Declaration
-----------

.. code-block:: cpp

	SoundID getSoundID(const Sound& sound);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - sound
	  - const :doc:`/types/Sound/index`\&
	  - Sound to load in the :doc:`/module/audio_module/index`.

Returns
-------

A unique :doc:`/types/SoundID/index` identifier for the image.

If the image could not be loaded, the returned value is ``NTSHENGN_SOUND_UNKNOWN``.