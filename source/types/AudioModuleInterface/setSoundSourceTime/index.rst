setSoundSourceTime
==================

:doc:`/types/AudioModuleInterface/index`::setSoundSourceTime

Sets the current time of a sound source.

Declaration
-----------

.. code-block:: cpp

	virtual void setSoundSourceTime(SoundSourceID soundSourceID, float newTime) = 0;

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
	* - newTime
	  - float
	  - The new current time of the sound source, **in seconds**.

Returns
-------

None.