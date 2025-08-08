isSoundSourceLooping
====================

:doc:`/types/AudioModuleInterface/index`::isSoundSourceLooping

Checks if a sound source is looping.

Declaration
-----------

.. code-block:: cpp

	virtual bool isSoundSourceLooping(SoundSourceID soundSourceID) = 0;

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
	  - The sound source to check the looping state of.

Returns
-------

``true`` if the sound source is looping, else, returns ``false``.