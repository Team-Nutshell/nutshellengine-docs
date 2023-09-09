setPitch
========

:doc:`/types/AudioModuleInterface/index`::setPitch

Sets the pitch of a sound.

Declaration
-----------

.. code-block:: cpp

	virtual void setPitch(SoundID soundID, float newPitch) = 0;

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
	* - newPitch
	  - float
	  - The new pitch of the sound.

Returns
-------

None.