setSoundSourceGain
==================

:doc:`/types/AudioModuleInterface/index`::setSoundSourceGain

Sets the gain of a sound source.

Declaration
-----------

.. code-block:: cpp

	virtual void setSoundSourceGain(SoundSourceID soundSourceID, float newGain) = 0;

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
	  - The sound source to change the gain of.
	* - newGain
	  - float
	  - The new gain of the sound source.

Returns
-------

None.