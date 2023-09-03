getSoundID
==========

Script::getSoundID

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
	  - const :doc:`/types/sound/index`\&
	  - Sound to load in the Audio Module.

Returns
-------

A unique :doc:`/types/sound_id/index` identifier for the image.

If the image could not be loaded, the returned value is ``NTSHENGN_SOUND_UNKNOWN``.