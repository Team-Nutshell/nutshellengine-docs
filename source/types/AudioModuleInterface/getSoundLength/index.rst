getSoundLength
==============

:doc:`/types/AudioModuleInterface/index`::getSoundLength

Returns the length of a sound.

Declaration
-----------

.. code-block:: cpp

	virtual float getSoundLength(SoundID soundID) = 0;

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
	  - The sound to get the length of.

Returns
-------

The length of the sound, **in seconds**.