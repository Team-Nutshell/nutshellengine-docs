getSoundSourcePosition
======================

:doc:`/types/AudioModuleInterface/index`::getSoundSourcePosition

Returns the position of a sound source.

Declaration
-----------

.. code-block:: cpp

	virtual Math::vec3 getSoundSourcePosition(SoundSourceID soundSourceID) = 0;

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
	  - The sound source to get the position of.

Returns
-------

The position of the sound source.