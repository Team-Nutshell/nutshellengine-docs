getSoundSourcePitch
===================

:doc:`/types/AudioModuleInterface/index`::getSoundSourcePitch

Returns the pitch of a sound source.

Declaration
-----------

.. code-block:: cpp

	virtual float getSoundSourcePitch(SoundSourceID soundSourceID) = 0;

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
	  - The sound source to get the pitch of.

Returns
-------

The pitch of the sound source.