isSoundPlaying
==============

:doc:`/types/AudioModuleInterface/index`::isSoundPlaying

Checks if any sound source of a certain sound is playing.

Declaration
-----------

.. code-block:: cpp

	virtual bool isSoundPlaying(SoundID soundID) = 0;

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
	  - The sound to check.

Returns
-------

``true`` if the sound has any sound source currently playing, else, returns ``false``.