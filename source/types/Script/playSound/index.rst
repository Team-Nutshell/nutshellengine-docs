
playSound
=========

:doc:`/types/Script/index`::playSound

Plays or resumes a sound.

Declaration
-----------

.. code-block:: cpp

	void playSound(SoundID soundID);

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
	  - The sound to play or resume.

Returns
-------

None.

Notes
-----

If the sound was not paused (either because it was never played before or because it was stopped using :doc:`/types/Script/stopSound/index`), the sound will play from the start.

If the sound was paused using :doc:`/types/Script/pauseSound/index`, the sound will resume from where it was paused.