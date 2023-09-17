pauseSoundSource
================

:doc:`/types/AudioModuleInterface/index`::pause

Pauses a playing sound source.

Declaration
-----------

.. code-block:: cpp

	virtual void pauseSoundSource(SoundSourceID soundSourceID) = 0;

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
	  - The playing sound source to pause.

Returns
-------

None.