playSoundAtPosition
===================

:doc:`/types/Script/index`::playSoundAtPosition

Plays a sound at a certain position and returns a unique identifier to this sound source.

Declaration
-----------

.. code-block:: cpp

	SoundSourceID playSoundAtPosition(SoundID soundID, const Math::vec3& position, float gain = 1.0f, float pitch = 1.0f, bool looping = false);

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
	* - position
	  - :doc:`/types/Math/index`::vec3
	  - The position to play the sound at.
	* - gain
	  - float
	  - The initial sound source gain.
	* - pitch
	  - float
	  - The initial sound source pitch.
	* - looping
	  - bool
	  - Whether the sound is looping or not.

Returns
-------

A unique :doc:`/types/SoundSourceID/index`.

Notes
-----

Each time this function is called, a new sound source will be played and a new :doc:`/types/SoundSourceID/index` will be returned.

If no listener :doc:`/types/Entity/index` has been set, the sound will be played globally.