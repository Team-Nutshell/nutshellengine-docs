SoundSourceState
================

Declaration
-----------

.. code-block:: cpp

	enum class SoundSourceState {
		Playing,
		Paused,
		Stopped
	};

Notes
-----

SoundSourceState is an enum used to give the state of a :doc:`/types/SoundSourceID/index`. ``Stopped`` either means that the sound source is not played anymore (and not paused) or that it never existed.