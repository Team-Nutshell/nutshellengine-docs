setSoundSourceLooping
=====================

:doc:`/types/AudioModuleInterface/index`::setSoundSourceLooping

Enables or disables looping on a sound source.

Declaration
-----------

.. code-block:: cpp

	virtual void setSoundSourceLooping(SoundSourceID soundSourceID, bool looping) = 0;

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
	* - looping
	  - bool
	  - Looping (``true``) or stopping when it ends (``false``).

Returns
-------

None.