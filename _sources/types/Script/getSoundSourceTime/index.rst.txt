getSoundSourceTime
==================

:doc:`/types/Sound/index`::getSoundSourceTime

Returns the current time of a sound source.

Declaration
-----------

.. code-block:: cpp

	float getSoundSourceTime(SoundSourceID soundSourceID);

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
	  - The sound source to get the current time of.

Returns
-------

The current time of the sound source, **in seconds**.