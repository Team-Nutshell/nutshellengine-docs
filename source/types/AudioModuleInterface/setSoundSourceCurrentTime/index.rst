setSoundSourceCurrentTime
=========================

:doc:`/types/AudioModuleInterface/index`::setSoundSourceCurrentTime

Sets the current time of a sound source.

Declaration
-----------

.. code-block:: cpp

	virtual void setSoundSourceCurrentTime(SoundSourceID soundSourceID, float newTime) = 0;

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

Notes
-----

If ``newTime`` is greater than the current's :doc:`/types/Sound/index`'s ``length``, the sound stops, unless ``soundSourceID`` is looping.