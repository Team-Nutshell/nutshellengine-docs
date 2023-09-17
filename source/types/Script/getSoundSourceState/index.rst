getSoundSourceState
===================

:doc:`/types/Script/index`::getSoundSourceState

Returns the state of a sound source.

Declaration
-----------

.. code-block:: cpp

	SoundSourceState getSoundSourceState(SoundSourceID soundSourceID);

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
	  - The sound source to get the state of.

Returns
-------

The sound source's :doc:`/types/SoundSourceState/index`.