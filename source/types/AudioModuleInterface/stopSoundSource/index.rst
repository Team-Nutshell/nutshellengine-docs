stopSoundSource
===============

:doc:`/types/AudioModuleInterface/index`::stopSoundSource

Stops a playing or paused sound.

Declaration
-----------

.. code-block:: cpp

	virtual void stopSoundSource(SoundSourceID soundSourceID) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - soundSourceID
	  - :doc:`/types/SoundSourceID/index`
	  - The sound source to stop.

Returns
-------

None.