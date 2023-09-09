getPitch
========

:doc:`/types/AudioModuleInterface/getGain/index`::getPitch

Returns the pitch of a sound.

Declaration
-----------

.. code-block:: cpp

	virtual float getPitch(SoundID soundID) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - soundID
	  - :doc:`/types/SoundID/index`
	  - The sound to get the pitch of.

Returns
-------

The pitch of the sound.