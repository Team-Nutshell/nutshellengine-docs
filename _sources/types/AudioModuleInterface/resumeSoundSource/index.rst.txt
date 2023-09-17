resumeSoundSource
=================

:doc:`/types/AudioModuleInterface/index`::resumeSoundSource

Resumes a paused sound source.

Declaration
-----------

.. code-block:: cpp

	virtual void resumeSoundSource(SoundSourceID soundSourceID) = 0;

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
	  - The paused sound source to resume.

Returns
-------

None.