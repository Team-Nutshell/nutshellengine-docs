playSound
=========

:doc:`/types/Script/index`::playSound

Plays a global sound and returns a unique identifier to this sound source.

Declaration
-----------

.. code-block:: cpp

	SoundSourceID playSound(SoundID soundID, float gain = 1.0f, float pitch = 1.0f, bool looping = false, float startTime = 0.0f);

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
	* - gain
	  - float
	  - The initial sound source gain.
	* - pitch
	  - float
	  - The initial sound source pitch.
	* - looping
	  - bool
	  - Whether the sound is looping or not.
	* - startTime
	  - float
	  - The start time of the sound.

Returns
-------

A unique :doc:`/types/SoundSourceID/index`.

Notes
-----

Each time this function is called, a new sound source will be played and a new :doc:`/types/SoundSourceID/index` will be returned.

If ``startTime`` is superior to the length of the sound, if ``looping`` is ``false``, the sound will stop directly, else, if ``looping`` is ``true``, the sound will start at ``startTime`` modulo the length of the sound.