getSoundSourceGain
==================

:doc:`/types/AudioModuleInterface/index`::getSoundSourceGain

Returns the gain of a sound source.

Declaration
-----------

.. code-block:: cpp

	virtual float getSoundSourceGain(SoundSourceID soundSourceID) = 0;

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
	  - The sound source to get the gain of.

Returns
-------

The gain of the sound source.